<Type Name="FabricClient+ServiceManagementClient" FullName="System.Fabric.FabricClient+ServiceManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ServiceManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceManagementClient = class" />
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
      <para><span data-ttu-id="1ca2c-101">管理する、サービスの有効化を表します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-101">Represents the enabling of the services to be managed.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceAsync (description As ServiceDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="1ca2c-102">サービスの構成。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-102">The configuration for the service.</span></span> <span data-ttu-id="1ca2c-103">A<see cref="T:System.Fabric.Description.ServiceDescription" />すべてのサービスを作成するために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-103">A <see cref="T:System.Fabric.Description.ServiceDescription" /> contains all of the information necessary to create a service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-104">指定された説明とサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-104">Instantiates a service with specified description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-105">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-105">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-106">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-106">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
          <para><span data-ttu-id="1ca2c-107">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-107">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-108"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-108">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-109">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-109">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-110">ときに<paramref name="description" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-110">When <paramref name="description" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription serviceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription serviceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync (serviceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para><span data-ttu-id="1ca2c-111">サービスの構成。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-111">The configuration for the service.</span></span> <span data-ttu-id="1ca2c-112">A<see cref="T:System.Fabric.Description.ServiceDescription" />すべてのサービスを作成するために必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-112">A <see cref="T:System.Fabric.Description.ServiceDescription" /> contains all of the information necessary to create a service.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-113">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-113">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-114"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-114">The <see cref="T:System.Threading.CancellationToken" />that the operation is observing.</span></span> <span data-ttu-id="1ca2c-115">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-115">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-116">指定された説明とサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-116">Instantiates a service with specified description.</span></span> <span data-ttu-id="1ca2c-117">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-117">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-118">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-118">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-119">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-119">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-120"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-120">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-121">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-121">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-122">ときに<paramref name="serviceDescription" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-122">When <paramref name="serviceDescription" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync serviceFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para><span data-ttu-id="1ca2c-123">アプリケーション マニフェストで指定されたサービス テンプレートから作成するサービスをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-123">Describes the Service to be created from service template specified in application manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-124">アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-124">Instantiates a service from the template specified in the Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-125">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-125">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-126">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-126">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-127"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-127">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-128">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-128">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="1ca2c-129"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-129"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: The service template does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="1ca2c-130">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-130">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="1ca2c-131">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-131">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (serviceFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para><span data-ttu-id="1ca2c-132">アプリケーション マニフェストで指定されたサービス テンプレートから作成するサービスをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-132">Describes a service to be created from service template specified in application manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-133">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-133">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-134"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-134">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-135">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-135">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-136">アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-136">Instantiates a service from the template specified in the Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-137">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-137">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-138">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-138">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-139"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-139">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-140">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-140">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="1ca2c-141"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-141"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: The service template does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="1ca2c-142">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-142">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="1ca2c-143">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-143">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="1ca2c-144">サービスが作成されるアプリケーションのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-144">The Service Fabric Name of the application under which the service will be created.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-145">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-145">The Service Fabric Name of the service.</span></span></para>
        </param>
        <param name="serviceTypeName">
          <para><span data-ttu-id="1ca2c-146">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-146">The name of the service type.</span></span> <span data-ttu-id="1ca2c-147">サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-147">This has to be same as the ServiceTypeName specified in the service manifest.</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="1ca2c-148">初期化データでは、サービスの作成者によって提供されるカスタム データを表します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-148">The initialization data represents the custom data provided by the creator of the service.</span></span> <span data-ttu-id="1ca2c-149">Service Fabric は、このデータを解析できません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-149">Service Fabric does not parse this data.</span></span> <span data-ttu-id="1ca2c-150">このデータはすべてのインスタンスまたは内のレプリカで利用可能になります<see cref="T:System.Fabric.StatefulServiceContext" />または<see cref="T:System.Fabric.StatelessServiceContext" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-150">This data would be available in every instance or replica in <see cref="T:System.Fabric.StatefulServiceContext" /> or <see cref="T:System.Fabric.StatelessServiceContext" />.</span></span>            
            <span data-ttu-id="1ca2c-151">これは、サービスを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-151">It cannot be changed after the service is created.</span></span> 
            </para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-152">アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-152">Instantiates a service from the template specified in the Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-153">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-153">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-154">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-154">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
          <para><span data-ttu-id="1ca2c-155">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-155">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-156"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-156">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-157">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-157">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="1ca2c-158"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません</span><span class="sxs-lookup"><span data-stu-id="1ca2c-158"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: The service template does not exist</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="1ca2c-159">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-159">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="1ca2c-160">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-160">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-161"><paramref name="applicationName" /> または <paramref name="serviceName" /> が null の場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-161">When <paramref name="applicationName" /> or <paramref name="serviceName" /> are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-162">ときに<paramref name="serviceTypeName" />が null またはホワイト スペースです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-162">When <paramref name="serviceTypeName" /> is null or white-space.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="1ca2c-163">サービスが作成されるアプリケーションのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-163">The Service Fabric Name of the application under which the service will be created.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-164">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-164">The Service Fabric Name of the service.</span></span></para>
        </param>
        <param name="serviceTypeName">
          <para><span data-ttu-id="1ca2c-165">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-165">The name of the service type.</span></span> <span data-ttu-id="1ca2c-166">サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-166">This has to be same as the ServiceTypeName specified in the service manifest.</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="1ca2c-167">初期化データでは、サービスの作成者によって提供されるカスタム データを表します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-167">The initialization data represents the custom data provided by the creator of the service.</span></span> <span data-ttu-id="1ca2c-168">Service Fabric は、このデータを解析できません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-168">Service Fabric does not parse this data.</span></span> <span data-ttu-id="1ca2c-169">このデータはすべてのインスタンスまたは内のレプリカで利用可能になります<see cref="T:System.Fabric.StatefulServiceContext" />または<see cref="T:System.Fabric.StatelessServiceContext" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-169">This data would be available in every instance or replica in <see cref="T:System.Fabric.StatefulServiceContext" /> or <see cref="T:System.Fabric.StatelessServiceContext" />.</span></span>            
            <span data-ttu-id="1ca2c-170">これは、サービスを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-170">It cannot be changed after the service is created.</span></span> 
            </para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-171">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-171">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-172"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-172">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-173">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-173">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-174">アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-174">Instantiates a service from the template specified in the Application Manifest.</span></span>
            <span data-ttu-id="1ca2c-175">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-175">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-176">インスタンス化されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-176">The instantiated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-177">既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-177">Service Fabric name will be implicitly created if it does not already exist.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-178"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-178">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-179">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-179">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="1ca2c-180"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-180"><see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: The service template does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="1ca2c-181">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-181">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="1ca2c-182">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-182">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-183"><paramref name="applicationName" /> または <paramref name="serviceName" /> が null の場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-183">When <paramref name="applicationName" /> or <paramref name="serviceName" /> are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-184">ときに<paramref name="serviceTypeName" />が null またはホワイト スペースです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-184">When <paramref name="serviceTypeName" /> is null or white-space.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync deleteServiceDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para><span data-ttu-id="1ca2c-185">削除するサービスの説明です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-185">The description of the service to be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-186">指定されたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-186">Deletes the specified service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-187">削除されたサービス インスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-187">The deleted service instance.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-188">サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-188">Service Fabric name will be implicitly and recursively deleted if the application is Service Fabric managed.</span></span></para>
          <para><span data-ttu-id="1ca2c-189">強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-189">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
          <para><span data-ttu-id="1ca2c-190">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-190">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-191"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-191">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-192">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-192">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-193">ときに<paramref name="deleteServiceDescription" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-193">When <paramref name="deleteServiceDescription" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-194">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-194">The Service Fabric name of the service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-195">指定されたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-195">Deletes the specified service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-196">削除されたサービス インスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-196">The deleted service instance.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-197">サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-197">Service Fabric name will be implicitly and recursively deleted if the application is Service Fabric managed.</span></span></para>
          <para><span data-ttu-id="1ca2c-198">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-198">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-199"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-199">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-200">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-200">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-201">ときに<paramref name="serviceName" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-201">When <paramref name="serviceName" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (deleteServiceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para><span data-ttu-id="1ca2c-202">削除するサービスの説明です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-202">The description of the service to be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-203">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-203">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-204"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-204">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-205">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-205">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-206">指定されたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-206">Deletes the specified service instance.</span></span>
            <span data-ttu-id="1ca2c-207">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-207">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-208">削除されたサービス インスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-208">The deleted service instance.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-209">サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-209">Service Fabric name will be implicitly and recursively deleted if the application is Service Fabric managed.</span></span></para>
          <para><span data-ttu-id="1ca2c-210">強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-210">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-211"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-211">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-212">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-212">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-213">ときに<paramref name="deleteServiceDescription" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-213">When <paramref name="deleteServiceDescription" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-214">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-214">The Service Fabric name of the service.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-215">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-215">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-216"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-216">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-217">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-217">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-218">指定されたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-218">Deletes the specified service instance.</span></span>
            <span data-ttu-id="1ca2c-219">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-219">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-220">削除されたサービス インスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-220">The deleted service instance.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-221">サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-221">Service Fabric name will be implicitly and recursively deleted if the application is Service Fabric managed.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-222"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-222">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-223">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-223">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-224">ときに<paramref name="serviceName" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-224">When <paramref name="serviceName" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceDescriptionAsync (serviceName As Uri) As Task(Of ServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-225">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-225">The Service Fabric Name of the service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-226">指定されたサービス インスタンスのサービスの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-226">Gets the Service Description for the specified service instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-227">指定されたサービス インスタンスのサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-227">The Service Description for the specified service instance.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-228">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-228">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-229"><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />名前がサービスに関連付けられているかどうかを判断する最も効率的な方法です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-229"><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" /> is the most efficient way of determining whether a name is associated with a service.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-230"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-230">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-231">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-231">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-232">ときに<paramref name="serviceName" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-232">When <paramref name="serviceName" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-233">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-233">The Service Fabric Name of the service.</span></span> </para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-234">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-234">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-235"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-235">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-236">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-236">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-237">指定されたサービス インスタンスのサービスの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-237">Gets the Service Description for the specified service instance.</span></span>
            <span data-ttu-id="1ca2c-238">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-238">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-239">指定されたサービス インスタンスのサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-239">The Service Description for the specified service instance.</span></span></para>
        </returns>
        <remarks>
          <para>
            <span data-ttu-id="1ca2c-240"><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />名前がサービスに関連付けられているかどうかを判断する最も効率的な方法です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-240"><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" /> is the most efficient way of determining whether a name is associated with a service.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-241"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-241">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-242">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-242">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-243">ときに<paramref name="serviceName" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-243">When <paramref name="serviceName" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestAsync (applicationTypeName As String, applicationTypeVersion As String, serviceManifestName As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="1ca2c-244">プロビジョニング済みのアプリケーション マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-244">The name of the provisioned application manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="1ca2c-245">プロビジョニング済みのアプリケーション マニフェストのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-245">The version of the provisioned application manifest.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="1ca2c-246">アプリケーション マニフェストで参照されたサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-246">The name of the service manifest referenced in the application manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-247">指定したアプリケーションの種類名およびアプリケーション タイプのバージョンでプロビジョニングされたサービス マニフェスト ドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-247">Gets the provisioned service manifest document in the specified application type name and application type version.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-248">プロビジョニングされたサービス マニフェストのドキュメント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-248">The provisioned service manifest document.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-249">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-249">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-250"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-250">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-251">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-251">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="1ca2c-252">プロビジョニング済みのアプリケーション マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-252">The name of the provisioned application manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="1ca2c-253">プロビジョニング済みのアプリケーション マニフェストのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-253">The version of the provisioned application manifest.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="1ca2c-254">アプリケーション マニフェストで参照されたサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-254">The name of the service manifest referenced in the application manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-255">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-255">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-256"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-256">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-257">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-257">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-258">指定したアプリケーションの種類名およびアプリケーション タイプのバージョンでプロビジョニングされたサービス マニフェスト ドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-258">Gets the provisioned service manifest document in the specified application type name and application type version.</span></span>
            <span data-ttu-id="1ca2c-259">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-259">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-260">プロビジョニングされたサービス マニフェスト ドキュメント</span><span class="sxs-lookup"><span data-stu-id="1ca2c-260">The provisioned service manifest document</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-261">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-261">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-262"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-262">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-263">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-263">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-264">場合<paramref name="applicationTypeName" />または<paramref name="applicationTypeVersion" />または<paramref name="serviceManifestName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-264">If <paramref name="applicationTypeName" /> or <paramref name="applicationTypeVersion" /> or <paramref name="serviceManifestName" /> are null/empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServiceNotificationFilterAsync (description As ServiceNotificationFilterDescription) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="1ca2c-265">どのサービス エンドポイントの変更イベントを決定する説明を使用してこのクライアントに配信する必要があります、<see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />イベント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-265">The description that determines which service endpoint change events should be delivered to this client through the <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> event.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-266">登録、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-266">Registers a <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-267">A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-267">A <see cref="T:System.Threading.Tasks.Task" /> representing the async operation.</span></span> <span data-ttu-id="1ca2c-268">タスクの結果は、登録されているに対応する ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />を使用して、同じフィルターの登録解除に使用できる<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-268">The task result is an ID corresponding to the registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> that can be used to unregister the same filter through <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-269">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-269">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-270">場合<paramref name="description" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-270">If <paramref name="description" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="1ca2c-271">どのサービス エンドポイントの変更イベントを決定する説明を使用してこのクライアントに配信する必要があります、<see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />イベント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-271">The description that determines which service endpoint change events should be delivered to this client through the <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> event.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-272">前に要求の処理時間の最大値が許可されている<see cref="T:System.TimeoutException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-272">The maximum time allowed for processing the request before <see cref="T:System.TimeoutException" /> is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-273">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-273">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-274">登録、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-274">Registers a <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</span></span>
            <span data-ttu-id="1ca2c-275">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-275">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-276">A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-276">A <see cref="T:System.Threading.Tasks.Task" /> representing the async operation.</span></span> <span data-ttu-id="1ca2c-277">タスクの結果は、登録されているに対応する ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />を使用して、同じフィルターの登録解除に使用できる<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-277">The task result is an ID corresponding to the registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> that can be used to unregister the same filter through <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-278">場合<paramref name="description" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-278">If <paramref name="description" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-279">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-279">The Service Fabric Name of the service.</span></span></para>
        </param>
        <param name="callback">
          <para><span data-ttu-id="1ca2c-280">この関数は、通知が到着したときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-280">The function that will be called when a notification arrives.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-281">この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-281">This API is deprecated, use <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-282">サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-282">The handler to be raised when the accessibility information of a service partition changes.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-283">通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-283">Notification will include changes on partition’s endpoints or exceptions that occurred while the information was being updated.</span></span> <span data-ttu-id="1ca2c-284">このオーバー ロードでは、シングルトンのパーティション分割されているサービス インスタンスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-284">This overload is used for Singleton partitioned service instances.</span></span> <span data-ttu-id="1ca2c-285">返される Int64 は、登録のコールバック ハンドル識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-285">Returned Int64 is the callback handle identifier for the registration.</span></span></para>
          <para><span data-ttu-id="1ca2c-286">通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-286">Notifications is a mechanism that delivers notifications to user’s code each time there is an service address change or an address resolution error related to a service partition the code has raised interest for.</span></span> <span data-ttu-id="1ca2c-287">こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-287">This way instead of resolving every time the current <see cref="T:System.Fabric.ResolvedServicePartition" /> becomes stale, program registers for updates.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-288"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-288">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-289">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-289">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-290">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-290">If <paramref name="serviceName" /> or <paramref name="callback" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, long partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Int64,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As Long, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * int64 * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-291">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-291">The Service Fabric Name of the service.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-292">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-292">The partition key for the service partition.</span></span></para>
        </param>
        <param name="callback">
          <para><span data-ttu-id="1ca2c-293">この関数は、通知が到着したときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-293">The function that will be called when a notification arrives.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-294">この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-294">This API is deprecated, use <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-295">サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-295">The handler to be raised when the accessibility information of a service partition changes.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-296">通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-296">Notification will include changes on partition’s endpoints or exceptions that occurred while the information was being updated.</span></span> <span data-ttu-id="1ca2c-297">このオーバー ロードでは、パーティション分割されている UniformInt64Range サービス インスタンスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-297">This overload is used for UniformInt64Range partitioned service instances.</span></span> <span data-ttu-id="1ca2c-298">返される Int64 は、登録のコールバック ハンドル識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-298">Returned Int64 is the callback handle identifier for the registration.</span></span></para>
          <para><span data-ttu-id="1ca2c-299">通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-299">Notifications is a mechanism that delivers notifications to user’s code each time there is an service address change or an address resolution error related to a service partition the code has raised interest for.</span></span> <span data-ttu-id="1ca2c-300">こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-300">This way instead of resolving every time the current <see cref="T:System.Fabric.ResolvedServicePartition" /> becomes stale, program registers for updates.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-301"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-301">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-302">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-302">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-303">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-303">If <paramref name="serviceName" /> or <paramref name="callback" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, string partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, string partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.String,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As String, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * string * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-304">サービスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-304">The Service Fabric Name of the service.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-305">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-305">The partition key for the service partition.</span></span></para>
        </param>
        <param name="callback">
          <para><span data-ttu-id="1ca2c-306">この関数は、通知が到着したときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-306">The function that will be called when a notification arrives.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-307">この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-307">This API is deprecated, use <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> instead.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-308">サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-308">The handler to be raised when the accessibility information of a service partition changes.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-309">通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-309">Notification will include changes on partition’s endpoints or exceptions that occurred while the information was being updated.</span></span> <span data-ttu-id="1ca2c-310">このオーバー ロードでは、名前付きのパーティション分割されているサービス インスタンスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-310">This overload is used for Named partitioned service instances.</span></span> <span data-ttu-id="1ca2c-311">返される Int64 は、登録のコールバック ハンドル識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-311">Returned Int64 is the callback handle identifier for the registration.</span></span></para>
          <para><span data-ttu-id="1ca2c-312">通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-312">Notifications is a mechanism that delivers notifications to user’s code each time there is an service address change or an address resolution error related to a service partition the code has raised interest for.</span></span> <span data-ttu-id="1ca2c-313">こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-313">This way instead of resolving every time the current <see cref="T:System.Fabric.ResolvedServicePartition" /> becomes stale, program registers for updates.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-314"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-314">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-315">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-315">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-316">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-316">If <paramref name="serviceName" /> or <paramref name="callback" /> are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-317">場合<paramref name="partitionKey" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-317">If <paramref name="partitionKey" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-318">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-318">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-319">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-319">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-320">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-320">The instance identifier.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-321">ノード上で実行されているサービス レプリカを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-321">Removes a service replica running on a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-322">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-322">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-323">この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-323">This API gives a running replica the chance to cleanup its state and be gracefully shutdown.</span></span> </para>
          <para><span data-ttu-id="1ca2c-324">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-324">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
          <para><span data-ttu-id="1ca2c-325">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-325">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-326">この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-326">Incorrect use of this API can lead to data loss for stateful services.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-327">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-327">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-328">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-328">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-329"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-329"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-331">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-331">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-332">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-332">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-333">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-333">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long, forceRemove As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-334">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-334">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-335">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-335">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-336">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-336">The instance identifier.</span></span></para>
        </param>
        <param name="forceRemove">
          <para><span data-ttu-id="1ca2c-337">正常にその状態をクリーンアップして閉じるできる必要があります、レプリカに指定するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="1ca2c-337">Specifies whether the replica should be given a chance to gracefully clean up its state and close</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-338">ノード上で実行されているサービス レプリカを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-338">Removes a service replica running on a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-339">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-339">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-340">この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-340">This API gives a running replica the chance to cleanup its state and be gracefully shutdown.</span></span> </para>
          <para><span data-ttu-id="1ca2c-341">ForceRemove フラグが設定されている場合、このような営業案件は指定されませんでした。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-341">If the forceRemove flag is set then no such opportunity is given.</span></span> <span data-ttu-id="1ca2c-342">Service Fabric がそのレプリカのホストを終了し、そのレプリカのすべての永続化された状態がリークします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-342">Service Fabric will terminate the host for that replica and any persisted state of that replica will be leaked.</span></span> </para>
          <para><span data-ttu-id="1ca2c-343">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-343">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-344">この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-344">Incorrect use of this API can lead to data loss for stateful services.</span></span></para>
          <para><span data-ttu-id="1ca2c-345">さらに、forceRemove フラグでは、同じプロセスでホストされているその他のすべてのレプリカに影響します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-345">In addition, the forceRemove flag impacts all other replicas hosted in the same process.</span></span></para>
          <para><span data-ttu-id="1ca2c-346">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-346">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-347">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-347">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-348">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-348">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-349"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-349"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-351">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-351">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-352">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-352">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-353">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-353">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-354">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-354">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-355">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-355">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-356">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-356">The instance identifier.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-357">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-357">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-358">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-358">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="1ca2c-359">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-359">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="1ca2c-360">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-360">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-361">ノード上で実行されているサービス レプリカを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-361">Removes a service replica running on a node.</span></span>
            <span data-ttu-id="1ca2c-362">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-362">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-363">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-363">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-364">この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-364">This API gives a running replica the chance to cleanup its state and be gracefully shutdown.</span></span> </para>
          <para><span data-ttu-id="1ca2c-365">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-365">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-366">この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-366">Incorrect use of this API can lead to data loss for stateful services.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-367">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-367">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-368">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-368">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-369"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-369"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-370"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-370"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-371">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-371">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-372">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-372">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-373">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-373">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-374">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-374">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-375">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-375">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-376">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-376">The instance identifier.</span></span></para>
        </param>
        <param name="forceRemove">
          <para><span data-ttu-id="1ca2c-377">正常にその状態をクリーンアップして閉じるできる必要があります、レプリカに指定するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="1ca2c-377">Specifies whether the replica should be given a chance to gracefully clean up its state and close</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-378">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-378">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-379">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-379">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="1ca2c-380">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-380">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="1ca2c-381">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-381">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-382">ノード上で実行されているサービス レプリカを削除します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-382">Removes a service replica running on a node.</span></span>
            <span data-ttu-id="1ca2c-383">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-383">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-384">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-384">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-385">この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-385">This API gives a running replica the chance to cleanup its state and be gracefully shutdown.</span></span> </para>
          <para><span data-ttu-id="1ca2c-386">ForceRemove フラグが設定されている場合、このような営業案件は指定されませんでした。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-386">If the forceRemove flag is set then no such opportunity is given.</span></span> <span data-ttu-id="1ca2c-387">Service Fabric がそのレプリカのホストを終了し、そのレプリカのすべての永続化された状態がリークします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-387">Service Fabric will terminate the host for that replica and any persisted state of that replica will be leaked.</span></span> </para>
          <para><span data-ttu-id="1ca2c-388">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-388">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-389">この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-389">Incorrect use of this API can lead to data loss for stateful services.</span></span></para>
          <para><span data-ttu-id="1ca2c-390">さらに、forceRemove フラグでは、同じプロセスでホストされているその他のすべてのレプリカに影響します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-390">In addition, the forceRemove flag impacts all other replicas hosted in the same process.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-391">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-391">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-392">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-392">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-393"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-393"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-394"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-394"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-395">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-395">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-396">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-396">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-397">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-397">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-398">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-398">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-399">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-399">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-400">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-400">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-401">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-401">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-402"><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />が返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-402">The <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-403">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-403">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-404"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-404">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-405">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-405">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-406">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-406">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-407">前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-407">The Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-408">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-408">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-409">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-409">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-410">API の解像度を苦情に基づいています。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-410">A complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-411">このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-411">This method will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-412">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-412">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span> </para>
          <para><span data-ttu-id="1ca2c-413">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-413">PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-414">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-414">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-415">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-415">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-416">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-416">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-417">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-417">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-418">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-418">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-419"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-419">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-420">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-420">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-421">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-421">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-422">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-422">The partition key for the service partition.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-423">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-423">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-424">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-424">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-425">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-425">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-426">このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-426">This method will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-427">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-427">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-428"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-428">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-429">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-429">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-430">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-430">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-431">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-431">The partition key for the service partition.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-432">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-432">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-433">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-433">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-434">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-434">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-435">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-435">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-436">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-436">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-437"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-437">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-438">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-438">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-439">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-439">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-440">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-440">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-441">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-441">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-442">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-442">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-443">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-443">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-444">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-444">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-445">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-445">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-446"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-446">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-447">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-447">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-448">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-448">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-449">前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-449">The Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-450">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-450">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-451">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-451">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-452">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-452">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-453">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-453">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-454">このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-454">This method will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-455">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-455">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-456">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-456">PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-457">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-457">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-458">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-458">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-459">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-459">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-460">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-460">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-461">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-461">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-462">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-462">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-463">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-463">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-464">前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-464">The Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-465">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-465">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-466">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-466">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-467">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-467">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-468">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-468">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-469">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-469">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span> </para>
          <para><span data-ttu-id="1ca2c-470">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-470">PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-471">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-471">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-472">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-472">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-473">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-473">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-474">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-474">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-475">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-475">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-476"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-476">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-477">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-477">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-478">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-478">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-479">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-479">The partition key for the service partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-480">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-480">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-481">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-481">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-482">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-482">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-483">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-483">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-484">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-484">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-485">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-485">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-486"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-486">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-487">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-487">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-488">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-488">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-489">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-489">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-490">前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-490">The previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-491">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-491">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-492">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-492">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-493">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-493">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-494">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-494">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-495">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-495">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-496">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-496">The PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-497">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-497">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-498">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-498">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-499">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-499">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-500">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-500">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-501">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-501">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-502"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-502">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-503">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-503">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-504">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-504">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-505">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-505">The partition key for the service partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-506">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-506">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-507">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-507">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-508">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-508">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-509">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-509">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-510">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-510">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-511">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-511">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-512"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-512">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-513">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-513">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-514">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-514">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-515">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-515">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-516"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-516">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-517">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-517">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-518">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-518">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-519">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-519">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-520">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-520">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-521">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-521">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-522">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-522">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-523"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-523">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-524">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-524">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-525">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-525">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-526">以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-526">Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-527">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-527">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-528"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-528">The <see cref="T:System.Threading.CancellationToken" />that the operation is observing.</span></span> <span data-ttu-id="1ca2c-529">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-529">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-530">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-530">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-531">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-531">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-532">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-532">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-533">このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-533">This method will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-534">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-534">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-535"><paramref name="previousResult" />引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-535"><paramref name="previousResult" /> argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-536">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-536">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-537">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-537">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-538">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-538">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-539">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。ResolveServicePartition なしで呼び出される、<paramref name="previousResult" />引数または<paramref name="previousResult" />引数を null に設定します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-539">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the <paramref name="previousResult" /> argument or <paramref name="previousResult" /> argument set to null.</span></span> <span data-ttu-id="1ca2c-540">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-540">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-541"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-541">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-542">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-542">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-543">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-543">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-544">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-544">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-545">以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-545">Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-546">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-546">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-547">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-547">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-548">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-548">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-549">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-549">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-550">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-550">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-551">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-551">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-552">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-552">PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-553">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-553">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-554">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-554">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-555">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-555">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-556">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-556">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-557">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-557">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-558"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-558">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-559">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-559">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-560">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-560">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-561">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-561">The partition key for the service partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-562">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-562">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-563"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-563">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-564">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-564">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-565">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-565">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-566">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-566">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-567">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-567">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-568">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-568">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-569">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-569">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-570"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-570">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-571">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-571">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-572">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-572">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-573">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-573">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-574">前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-574">The previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-575">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-575">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-576">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-576">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-577">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-577">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-578">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-578">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-579">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-579">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-580">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-580">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-581">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-581">The PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-582">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-582">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-583">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-583">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-584">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-584">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-585">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-585">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-586">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-586">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-587"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-587">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-588">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-588">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-589">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-589">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-590">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-590">The partition key for the service partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-591">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-591">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-592"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-592">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-593">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-593">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-594">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-594">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-595">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-595">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-596">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-596">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-597">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-597">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-598">このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-598">When this overload is used, the system will always return the closest <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-599"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-599">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-600">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-600">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-601">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-601">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-602">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-602">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-603">以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-603">Previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-604">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-604">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="1ca2c-605"><see cref="T:System.Threading.CancellationToken" />操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-605"><see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-606">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-606">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-607">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-607">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-608">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-608">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-609">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-609">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-610">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-610">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-611">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-611">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-612">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-612">PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-613">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-613">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-614">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-614">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-615">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-615">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-616">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-616">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-617">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-617">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-618"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-618">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-619">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-619">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="1ca2c-620">サービス インスタンスのサービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-620">The Service Fabric Name of the service instance.</span></span></para>
        </param>
        <param name="partitionKey">
          <para><span data-ttu-id="1ca2c-621">サービス パーティションのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-621">The partition key for the service partition.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="1ca2c-622">前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-622">The previous <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition that the user believes is stale.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-623">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-623">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-624"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-624">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-625">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-625">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-626">指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-626">Queries the system for the set of endpoints the specified service partition is listening to.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-627">指定したサービス パーティションがリッスンしている一連のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-627">The set of endpoints the specified service partition is listening to.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-628">これは、準拠しているベース解決 API です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-628">This is a complaint based resolution API.</span></span></para>
          <para><span data-ttu-id="1ca2c-629">返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-629">This will return a <see cref="T:System.Fabric.ResolvedServicePartition" /> for the specified service partition.</span></span> <span data-ttu-id="1ca2c-630">このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-630">When this overload is used, the system will return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> than the “previousResult” argument if it is available.</span></span></para>
          <para><span data-ttu-id="1ca2c-631">PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-631">The PreviousResult argument enables the user to say ”This is the previous list of endpoints for this Service partition.</span></span> <span data-ttu-id="1ca2c-632">エンドポイントを試行し、それらが古くなっていないと思います。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-632">I have tried the endpoints and I believe they are stale.</span></span> <span data-ttu-id="1ca2c-633">返す me このセットの最新バージョンです。"</span><span class="sxs-lookup"><span data-stu-id="1ca2c-633">Return me a more up to date version of this set.”</span></span> <span data-ttu-id="1ca2c-634">この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-634">In this case, the system will try to return a more up-to-date <see cref="T:System.Fabric.ResolvedServicePartition" /> in the most efficient way possible.</span></span> <span data-ttu-id="1ca2c-635">新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-635">If no newer version can be found, a <see cref="T:System.Fabric.ResolvedServicePartition" /> with the same version will be returned.ResolveServicePartition can be called without the previousResult argument or previousResult argument set to null.</span></span> <span data-ttu-id="1ca2c-636">システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-636">As no prerequisite is specified, the system will return the closest copy of the <see cref="T:System.Fabric.ResolvedServicePartition" /> for the service partition.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-637"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-637">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-638">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-638">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-639">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-639">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-640">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-640">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-641">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-641">The instance identifier.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-642">ノード上で実行されている永続化されたサービスのサービス レプリカを再起動します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-642">Restarts a service replica of a persisted service running on a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-643">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-643">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-644">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-644">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-645">この API の不適切な使用は、ステートフル サービスの可用性の損失につながる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-645">Incorrect use of this API can lead to availability loss for stateful services.</span></span></para>
          <para><span data-ttu-id="1ca2c-646">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-646">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-647">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-647">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-648">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-648">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-649"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-649"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-650"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-650"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-651">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-651">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-652"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />レプリカは、ステートフルな永続化されたサービスに属していないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-652"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" /> is returned if the replica does not belong to a stateful persisted service.</span></span> <span data-ttu-id="1ca2c-653">のみステートフルな永続化されたレプリカを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-653">Only stateful persisted replicas can be restarted.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-654">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-654">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-655">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-655">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="1ca2c-656">ノード名。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-656">The name of the node.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="1ca2c-657">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-657">The partition identifier.</span></span></para>
        </param>
        <param name="replicaOrInstanceId">
          <para><span data-ttu-id="1ca2c-658">インスタンス識別子。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-658">The instance identifier.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-659">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-659">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-660">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-660">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="1ca2c-661">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-661">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="1ca2c-662">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-662">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-663">ノード上で実行されている永続化されたサービスのサービス レプリカを再起動します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-663">Restarts a service replica of a persisted service running on a node.</span></span>
            <span data-ttu-id="1ca2c-664">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-664">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-665">要求の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-665">A Task representing the acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-666">警告: この API を使用する場合に実行される安全性チェックはありません。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-666">WARNING: There are no safety checks performed when this API is used.</span></span> <span data-ttu-id="1ca2c-667">この API の不適切な使用は、ステートフル サービスの可用性の損失につながる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-667">Incorrect use of this API can lead to availability loss for stateful services.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="1ca2c-668">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-668">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="1ca2c-669">参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-669">See <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="1ca2c-670"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-670"><see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" /> is returned if the replica or instance id is not running on the node.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" /> is returned if the replica or instance id cannot be restarted or removed at this time as it is in an invalid state.</span></span> <span data-ttu-id="1ca2c-672">レプリカは既に閉じられている処理を行ってです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-672">For example, the replica is already in the process of being closed.</span></span></para>
          <para>
            <span data-ttu-id="1ca2c-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />レプリカは、ステートフルな永続化されたサービスに属していないかどうかが返されます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" /> is returned if the replica does not belong to a stateful persisted service.</span></span> <span data-ttu-id="1ca2c-674">のみステートフルな永続化されたレプリカを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-674">Only stateful persisted replicas can be restarted.</span></span></para>
          <para>
                <span data-ttu-id="1ca2c-675">関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-675">See also <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1ca2c-676">場合<paramref name="nodeName" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-676">If <paramref name="nodeName" /> is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceNotificationFilterMatched">
      <MemberSignature Language="C#" Value="public event EventHandler ServiceNotificationFilterMatched;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ServiceNotificationFilterMatched" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />
      <MemberSignature Language="VB.NET" Value="Public Event ServiceNotificationFilterMatched As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ServiceNotificationFilterMatched : EventHandler " Usage="member this.ServiceNotificationFilterMatched : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1ca2c-677">いつ発生するか、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって以前登録<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />システムで、サービスのエンドポイントの変更と一致します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-677">Raised when a <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> previously registered through <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> is matched by a service's endpoint changes in system.</span></span></para>
        </summary>
        <remarks>
            <span data-ttu-id="1ca2c-678">イベント引数の型が<see cref="T:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationEventArgs" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-678">The event argument is of type <see cref="T:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationEventArgs" />.</span></span>
            </remarks>
        <example>
            <span data-ttu-id="1ca2c-679">次の例では、登録し、サービスの通知を処理する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-679">The following example shows how to register for and process service notifications:</span></span>
            <code language="cs">
            namespace ServiceNotificationsExample
            {
                class Program
                {
                    static void Main(string[] args)
                    {
                        var client = new FabricClient(new string[] { "[cluster_endpoint]:[client_port]" });
            
                        var filter = new ServiceNotificationFilterDescription()
                        {
                            Name = new Uri("fabric:/my_application"),
                            MatchNamePrefix = true,
                        };
            
                        client.ServiceManager.ServiceNotificationFilterMatched += (s, e) =&gt; OnNotification(e);
            
                        var filterId = client.ServiceManager.RegisterServiceNotificationFilterAsync(filter).Result;
            
                        Console.WriteLine(
                            "Registered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
            
                        Console.ReadLine();
            
                        client.ServiceManager.UnregisterServiceNotificationFilterAsync(filterId).Wait();
            
                        Console.WriteLine(
                            "Unregistered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
                    }
            
                    private static void OnNotification(EventArgs e)
                    {
                        var castedEventArgs = (FabricClient.ServiceManagementClient.ServiceNotificationEventArgs)e;
            
                        var notification = castedEventArgs.Notification;
            
                        Console.WriteLine(
                            "[{0}] received notification for service '{1}'",
                            DateTime.UtcNow,
                            notification.ServiceName);
                    }
                }
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterServiceNotificationFilterAsync (filterId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync filterId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para><span data-ttu-id="1ca2c-680">以前に登録済みの ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />から返された<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-680">The ID of a previously registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> returned from <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-681">以前に登録されてから登録解除<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-681">Unregisters a previously registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-682">A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-682">A <see cref="T:System.Threading.Tasks.Task" /> representing the async operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-683">クライアント自体はすべて使用できなく個々 のフィルターの登録を解除する必要はありません<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって登録されているオブジェクト、<see cref="T:System.Fabric.FabricClient" />されません自動的に登録されているクライアントが破棄されるときにします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-683">It's not necessary to unregister individual filters if the client itself will no longer be used since all <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> objects registered by the <see cref="T:System.Fabric.FabricClient" /> will be automatically unregistered when client is disposed.</span></span></para>
          <para><span data-ttu-id="1ca2c-684">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-684">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync (filterId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para><span data-ttu-id="1ca2c-685">以前に登録済みの ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />から返された<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-685">The ID of a previously registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> returned from <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-686">前に要求の処理時間の最大値が許可されている<see cref="T:System.TimeoutException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-686">The maximum time allowed for processing the request before <see cref="T:System.TimeoutException" /> is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-687">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-687">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-688">以前に登録されてから登録解除<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-688">Unregisters a previously registered <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-689">A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-689">A <see cref="T:System.Threading.Tasks.Task" /> representing the async operation.</span></span></para>
        </returns>
        <remarks>
            <span data-ttu-id="1ca2c-690">クライアント自体はすべて使用できなく個々 のフィルターの登録を解除する必要はありません<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって登録されているオブジェクト、<see cref="T:System.Fabric.FabricClient" />されません自動的に登録されているクライアントが破棄されるときにします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-690">It's not necessary to unregister individual filters if the client itself will no longer be used since all <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> objects registered by the <see cref="T:System.Fabric.FabricClient" /> will be automatically unregistered when client is disposed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public void UnregisterServicePartitionResolutionChangeHandler (long callbackHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnregisterServicePartitionResolutionChangeHandler(int64 callbackHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServicePartitionResolutionChangeHandler(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UnregisterServicePartitionResolutionChangeHandler (callbackHandle As Long)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServicePartitionResolutionChangeHandler : int64 -&gt; unit" Usage="serviceManagementClient.UnregisterServicePartitionResolutionChangeHandler callbackHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackHandle" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="callbackHandle">
          <para><span data-ttu-id="1ca2c-691">削除される callbackHandle 識別子です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-691">The callbackHandle identifier that will be removed.</span></span> <span data-ttu-id="1ca2c-692">これは、によって返される、<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-692">This is returned by the <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" /> call.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-693">以前に登録されている変更ハンドラーの登録解除<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-693">Unregisters a change handler previously registered with <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-694"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-694">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="1ca2c-695">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-695">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceAsync (name As Uri, updateDescription As ServiceUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, updateDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="1ca2c-696">更新中、サービスの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-696">The URI name of the service being updated.</span></span></para>
        </param>
        <param name="updateDescription">
          <para><span data-ttu-id="1ca2c-697"><see cref="T:System.Fabric.Description.ServiceUpdateDescription" />サービスの更新された構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-697">The <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> that specifies the updated configuration for the service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-698">指定された説明では、サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-698">Updates a service with the specified description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-699">更新されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-699">The updated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-700">既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-700">The default timeout is one minute for which the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span> </para>
          <para><span data-ttu-id="1ca2c-701">注: を安全に両方を増やすには、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />と<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />最初を増やす、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />を作成して向上し、さらにレプリカを待機し、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></span><span class="sxs-lookup"><span data-stu-id="1ca2c-701">NOTE: To safely increase both the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> and the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> first increase the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> and wait for additional replicas to be created and then increase the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-702"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-702">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span>
            <span data-ttu-id="1ca2c-703">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-703">Dispose of the<see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-704"><paramref name="name" /> または <paramref name="updateDescription" /> が null の場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-704">When <paramref name="name" /> or <paramref name="updateDescription" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, serviceUpdateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="serviceUpdateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="1ca2c-705">更新中、サービスの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-705">The URI name of the service being updated.</span></span></para>
        </param>
        <param name="serviceUpdateDescription">
          <para><span data-ttu-id="1ca2c-706"><see cref="T:System.Fabric.Description.ServiceUpdateDescription" />サービスの更新された構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-706">The <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> that specifies the updated configuration for the service.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="1ca2c-707">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-707">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="1ca2c-708"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-708">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="1ca2c-709">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-709">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="1ca2c-710">指定された説明では、サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-710">Updates a service with the specified description.</span></span>
            <span data-ttu-id="1ca2c-711">これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-711">Also takes in timeout interval, which is the maximum of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" /> and cancellation-token that the operation is observing.</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="1ca2c-712">更新されたサービスです。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-712">The updated service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="1ca2c-713">注: を安全に両方を増やすには、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />と<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />最初を増やす、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />を作成して向上し、さらにレプリカを待機し、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></span><span class="sxs-lookup"><span data-stu-id="1ca2c-713">NOTE: To safely increase both the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> and the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> first increase the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> and wait for additional replicas to be created and then increase the <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="1ca2c-714"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-714">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span>
            <span data-ttu-id="1ca2c-715">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-715">Dispose of the<see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1ca2c-716"><paramref name="name" /> または <paramref name="serviceUpdateDescription" /> が null の場合。</span><span class="sxs-lookup"><span data-stu-id="1ca2c-716">When <paramref name="name" /> or <paramref name="serviceUpdateDescription" /> are null.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>