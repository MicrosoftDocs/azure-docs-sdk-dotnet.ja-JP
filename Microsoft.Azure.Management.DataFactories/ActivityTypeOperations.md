<Type Name="ActivityTypeOperations" FullName="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations">
  <TypeSignature Language="C#" Value="public class ActivityTypeOperations : Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityTypeOperations extends System.Object implements class Hyak.Common.IServiceOperations`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityTypeOperations&#xA;Implements IActivityTypeOperations, IServiceOperations(Of DataFactoryManagementClient)" />
  <TypeSignature Language="F#" Value="type ActivityTypeOperations = class&#xA;    interface IServiceOperations&lt;DataFactoryManagementClient&gt;&#xA;    interface IActivityTypeOperations" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.IActivityTypeOperations</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="614ec-101">データ ファクトリ Activitytype を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="614ec-101">Operations for managing data factory ActivityTypes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-102">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-102">Required.</span></span> <span data-ttu-id="614ec-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-104">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-104">Required.</span></span> <span data-ttu-id="614ec-105">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-105">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="614ec-106">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-106">Required.</span></span> <span data-ttu-id="614ec-107">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-107">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-108">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-109">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="614ec-109">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-110">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="614ec-110">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Client As DataFactoryManagementClient" />
      <MemberSignature Language="F#" Value="member this.Client : Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-111">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-111">Required.</span></span> <span data-ttu-id="614ec-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-113">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-113">Required.</span></span> <span data-ttu-id="614ec-114">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-114">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="614ec-115">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-115">Required.</span></span> <span data-ttu-id="614ec-116">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="614ec-116">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-118">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="614ec-118">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-119">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="614ec-119">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, activityTypeName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateWithRawJsonContentAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-120">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-120">Required.</span></span> <span data-ttu-id="614ec-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-122">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-122">Required.</span></span> <span data-ttu-id="614ec-123">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-123">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="614ec-124">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-124">Required.</span></span> <span data-ttu-id="614ec-125">ActivityType の名。</span><span class="sxs-lookup"><span data-stu-id="614ec-125">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="614ec-126">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-126">Required.</span></span> <span data-ttu-id="614ec-127">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="614ec-127">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-129">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="614ec-129">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-130">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="614ec-130">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.DeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;DeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-131">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-131">Required.</span></span> <span data-ttu-id="614ec-132">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-133">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-133">Required.</span></span> <span data-ttu-id="614ec-134">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-134">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="614ec-135">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-135">Required.</span></span> <span data-ttu-id="614ec-136">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-136">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-138">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="614ec-138">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-139">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="614ec-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;&#xA;override this.GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="activityTypeOperations.GetAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-140">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-140">Required.</span></span> <span data-ttu-id="614ec-141">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-141">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-142">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-142">Required.</span></span> <span data-ttu-id="614ec-143">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-143">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="614ec-144">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-144">Required.</span></span> <span data-ttu-id="614ec-145">ActivityType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="614ec-145">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-147">ActivityType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="614ec-147">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-148">ActivityType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="614ec-148">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="614ec-149">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-149">Required.</span></span> <span data-ttu-id="614ec-150">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="614ec-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="614ec-151">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-151">Required.</span></span> <span data-ttu-id="614ec-152">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="614ec-152">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="614ec-153">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-153">Required.</span></span> <span data-ttu-id="614ec-154">ActivityType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="614ec-154">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-156">次のページへのリンクを持つ ActivityType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="614ec-156">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-157">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="614ec-157">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="614ec-158">必須。</span><span class="sxs-lookup"><span data-stu-id="614ec-158">Required.</span></span> <span data-ttu-id="614ec-159">[次へ] の [Activitytype] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="614ec-159">The url to the next ActivityTypes page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="614ec-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="614ec-160">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="614ec-161">次のページへのリンクを持つ ActivityType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="614ec-161">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="614ec-162">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="614ec-162">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>