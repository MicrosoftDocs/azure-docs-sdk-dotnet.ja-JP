<Type Name="FabricClient+ServiceGroupManagementClient" FullName="System.Fabric.FabricClient+ServiceGroupManagementClient">
  <TypeSignature Language="C#" Value="public class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit FabricClient/ServiceGroupManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceGroupManagementClient = class" />
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
      <para><span data-ttu-id="e74d4-101">により、クライアント側の作成、削除、およびクラスター内のサービス グループの検査と同じように、<see cref="T:System.Fabric.FabricClient.ServiceManagementClient" />正規サービス。</span><span class="sxs-lookup"><span data-stu-id="e74d4-101">Allows client side creation, deletion, and inspection of service groups inside the cluster, just like the <see cref="T:System.Fabric.FabricClient.ServiceManagementClient" /> for regular services.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupAsync (description As ServiceGroupDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e74d4-102"><see cref="T:System.Fabric.Description.ServiceGroupDescription" />グループとそのメンバーをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-102">The <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> which describes the group and its members.</span></span></param>
        <summary>
            <span data-ttu-id="e74d4-103">非同期的にグループを作成、サービスから、指定された<see cref="T:System.Fabric.Description.ServiceGroupDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-103">Asynchronously creates a service group from the given <see cref="T:System.Fabric.Description.ServiceGroupDescription" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e74d4-104">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-104">The task representing the asynchronous service group creation operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e74d4-105"><see cref="T:System.Fabric.Description.ServiceGroupDescription" />グループとそのメンバーをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-105">The <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> which describes the group and its members.</span></span></param>
        <param name="timeout"><span data-ttu-id="e74d4-106">Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-106">Timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a Timeout Exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e74d4-107"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-107">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span>  <span data-ttu-id="e74d4-108">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-108">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="e74d4-109">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e74d4-109">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></param>
        <summary>
            <span data-ttu-id="e74d4-110">サービス グループを非同期に作成、特定<see cref="T:System.Fabric.Description.ServiceGroupDescription" />で指定したタイムアウトと<see cref="T:System.Threading.CancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-110">Asynchronously creates a service group from the given <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> with the provided timeout and <see cref="T:System.Threading.CancellationToken" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e74d4-111">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-111">The task representing the asynchronous service group creation operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync serviceGroupFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para><span data-ttu-id="e74d4-112">アプリケーション マニフェストで指定されたサービスのグループ テンプレートから作成される、サービスのグループについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-112">Describes the Service Group to be created from Service Group Template specified in Application Manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-113">現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-113">Creates a service group from a Service Group Template that is pre-defined in the current Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-114">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-114">The task representing the asynchronous service group creation operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (serviceGroupFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para><span data-ttu-id="e74d4-115">アプリケーション マニフェストで指定されたサービスのグループ テンプレートから作成される、サービスのグループについて説明します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-115">Describes the Service Group to be created from Service Group Template specified in Application Manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e74d4-116">最大許容時間、操作を完了するまで、TimeoutException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="e74d4-116">Maximum allowed time for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e74d4-117"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="e74d4-117">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="e74d4-118">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-118">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="e74d4-119">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e74d4-119">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-120">現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-120">Creates a service group from a Service Group Template that is pre-defined in the current Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-121">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-121">The task representing the asynchronous service group creation operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
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
          <para><span data-ttu-id="e74d4-122">サービス グループのアプリケーション名</span><span class="sxs-lookup"><span data-stu-id="e74d4-122">Application name for the Service Group</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="e74d4-123">サービス グループのサービス名</span><span class="sxs-lookup"><span data-stu-id="e74d4-123">Service name for the Service Group</span></span></para>
        </param>
        <param name="serviceTypeName">
          <para><span data-ttu-id="e74d4-124">サービス グループのサービスの種類名</span><span class="sxs-lookup"><span data-stu-id="e74d4-124">Service Type Name for the Service Group</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="e74d4-125">サービス グループのインスタンスに渡す初期化データ</span><span class="sxs-lookup"><span data-stu-id="e74d4-125">Initialization data to pass into the Service Group instance</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-126">現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-126">Creates a Service Group from a Service Group Template that is pre-defined in the current Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-127">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-127">The task representing the asynchronous service group creation operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
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
          <para><span data-ttu-id="e74d4-128">サービス グループのアプリケーション名</span><span class="sxs-lookup"><span data-stu-id="e74d4-128">Application name for the Service Group</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="e74d4-129">サービス グループのサービス名</span><span class="sxs-lookup"><span data-stu-id="e74d4-129">Service name for the Service Group</span></span></para>
        </param>
        <param name="serviceTypeName">
          <para><span data-ttu-id="e74d4-130">サービス グループのサービスの種類名</span><span class="sxs-lookup"><span data-stu-id="e74d4-130">Service Type Name for the Service Group</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="e74d4-131">サービス グループのインスタンスに渡す初期化データ</span><span class="sxs-lookup"><span data-stu-id="e74d4-131">Initialization data to pass into the Service Group instance</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e74d4-132">最大許容時間、操作を完了するまで、TimeoutException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="e74d4-132">Maximum allowed time for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e74d4-133"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="e74d4-133">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="e74d4-134">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-134">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="e74d4-135">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e74d4-135">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-136">現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-136">Creates a service group from a Service Group Template that is pre-defined in the current Application Manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-137">非同期サービス グループの作成操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-137">The task representing the asynchronous service group creation operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceGroupAsync (serviceGroupName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para><span data-ttu-id="e74d4-138">削除するサービス グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e74d4-138">The name of the service group to be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-139">非同期的に、指定されたサービスのグループを削除します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-139">Asynchronously deletes the specified service group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-140">非同期サービス グループを表すタスクでは、操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-140">The task representing the asynchronous service group delete operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e74d4-141"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="e74d4-141">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e74d4-142">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-142">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para><span data-ttu-id="e74d4-143">削除するサービス グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e74d4-143">The name of the service group to be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e74d4-144">Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-144">Timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a Timeout Exception.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e74d4-145"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-145">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span>  <span data-ttu-id="e74d4-146">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-146">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="e74d4-147">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e74d4-147">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-148">指定したタイムアウトで指定されたサービスのグループを非同期に削除し、<see cref="T:System.Threading.CancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-148">Asynchronously deletes the specified service group with the provided timeout and <see cref="T:System.Threading.CancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-149">非同期サービス グループを表すタスクでは、操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-149">The task representing the asynchronous service group delete operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e74d4-150"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="e74d4-150">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e74d4-151">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-151">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupDescriptionAsync (serviceGroupName As Uri) As Task(Of ServiceGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para><span data-ttu-id="e74d4-152">サービスの名前でグループ化が<see cref="T:System.Fabric.Description.ServiceGroupDescription" />フェッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e74d4-152">The name of the service group whose <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> should be fetched.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-153">非同期的にフェッチ、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />存在する場合、指定したサービス グループにします。</span><span class="sxs-lookup"><span data-stu-id="e74d4-153">Asynchronously fetches the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> for the specified service group, if it exists.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-154">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-154">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e74d4-155"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="e74d4-155">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e74d4-156">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-156">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para><span data-ttu-id="e74d4-157">サービスの名前でグループ化が<see cref="T:System.Fabric.Description.ServiceGroupDescription" />フェッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e74d4-157">The name of the service group whose <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> should be fetched.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e74d4-158">Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-158">Timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a Timeout Exception.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e74d4-159"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="e74d4-159">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="e74d4-160">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-160">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="e74d4-161">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e74d4-161">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e74d4-162">非同期的にフェッチ、 <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> 、指定したサービス グループを指定したタイムアウトで、存在する場合と<see cref="T:System.Threading.CancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-162">Asynchronously fetches the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> for the specified service group, if it exists, with the provided timeout and <see cref="T:System.Threading.CancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e74d4-163">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="e74d4-163">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e74d4-164"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="e74d4-164">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e74d4-165">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="e74d4-165">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceGroupAsync (name As Uri, updateDescription As ServiceGroupUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription)" />
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
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e74d4-166">更新中のサービス グループの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-166">The URI name of the service group being updated.</span></span></param>
        <param name="updateDescription"><span data-ttu-id="e74d4-167"><see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" />サービス グループの更新された構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-167">The <see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" /> that specifies the updated configuration for the service group.</span></span></param>
        <summary>
            <span data-ttu-id="e74d4-168">指定された説明を持つサービス グループを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-168">Asynchronously updates a service group with the specified description.</span></span>
            </summary>
        <returns><span data-ttu-id="e74d4-169">非同期サービス グループを表すタスクでは、操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-169">The task representing the asynchronous service group update operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription, timeout, cancellationToken)" />
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
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e74d4-170">更新中、サービスの URI 名です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-170">The URI name of the service being updated.</span></span></param>
        <param name="updateDescription"><span data-ttu-id="e74d4-171"><see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" />サービスの更新された構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-171">The <see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" /> that specifies the updated configuration for the service.</span></span></param>
        <param name="timeout"><span data-ttu-id="e74d4-172">システムで返す前に実行するには、この API は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="e74d4-172">The maximum amount of time the system will allow this API to take before returning <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e74d4-173"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="e74d4-173">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="e74d4-174">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-174">It can be used to propagate notification that the operation should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="e74d4-175">指定された説明を持つサービス グループを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-175">Asynchronously updates a service group with specified description.</span></span>
            </summary>
        <returns><span data-ttu-id="e74d4-176">非同期サービス グループを表すタスクでは、操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="e74d4-176">The task representing the asynchronous service group update operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>