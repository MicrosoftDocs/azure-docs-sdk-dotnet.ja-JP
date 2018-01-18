<Type Name="ISnapshotsOperations" FullName="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations">
  <TypeSignature Language="C#" Value="public interface ISnapshotsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISnapshotsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISnapshotsOperations" />
  <TypeSignature Language="F#" Value="type ISnapshotsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="691fd-101">SnapshotsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="691fd-101">SnapshotsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="iSnapshotsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, snapshotName, snapshot, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-102">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-103">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-103">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="691fd-104">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="691fd-104">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-107">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="691fd-107">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string snapshotName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iSnapshotsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, snapshotName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-111">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-112">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-112">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-115">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="691fd-115">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt; BeginGrantAccessWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt; BeginGrantAccessWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.BeginGrantAccessWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGrantAccessWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt;" Usage="iSnapshotsOperations.BeginGrantAccessWithHttpMessagesAsync (resourceGroupName, snapshotName, grantAccessData, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-119">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-119">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-120">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-120">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="691fd-121">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="691fd-121">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-124">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="691fd-124">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginRevokeAccessWithHttpMessagesAsync (string resourceGroupName, string snapshotName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginRevokeAccessWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.BeginRevokeAccessWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRevokeAccessWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iSnapshotsOperations.BeginRevokeAccessWithHttpMessagesAsync (resourceGroupName, snapshotName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-128">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-129">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-129">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-132">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="691fd-132">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="iSnapshotsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, snapshotName, snapshot, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-136">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-137">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-137">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="691fd-138">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="691fd-138">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-141">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="691fd-141">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-143">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="iSnapshotsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, snapshotName, snapshot, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-145">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-146">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-146">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="691fd-147">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="691fd-147">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-150">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="691fd-150">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string snapshotName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iSnapshotsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, snapshotName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-154">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-155">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-155">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-158">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="691fd-158">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string snapshotName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="iSnapshotsOperations.GetWithHttpMessagesAsync (resourceGroupName, snapshotName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-162">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-162">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-163">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-163">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-166">スナップショットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="691fd-166">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-167">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-167">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-168">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-168">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-169">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt; GrantAccessWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt; GrantAccessWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.GrantAccessWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GrantAccessWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt;" Usage="iSnapshotsOperations.GrantAccessWithHttpMessagesAsync (resourceGroupName, snapshotName, grantAccessData, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-170">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-170">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-171">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-171">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="691fd-172">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="691fd-172">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-175">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="691fd-175">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;" Usage="iSnapshotsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="691fd-179">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="691fd-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-182">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="691fd-182">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;" Usage="iSnapshotsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-186">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-186">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-189">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="691fd-189">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;" Usage="iSnapshotsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="691fd-193">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="691fd-193">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-194">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-194">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-196">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="691fd-196">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-197">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-198">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-199">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;" Usage="iSnapshotsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="691fd-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-202">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="691fd-202">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; RevokeAccessWithHttpMessagesAsync (string resourceGroupName, string snapshotName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; RevokeAccessWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.RevokeAccessWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RevokeAccessWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iSnapshotsOperations.RevokeAccessWithHttpMessagesAsync (resourceGroupName, snapshotName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-206">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-206">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-207">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-207">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-210">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="691fd-210">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-212">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-212">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-213">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="iSnapshotsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, snapshotName, snapshot, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="691fd-214">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-214">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="691fd-215">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="691fd-215">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="691fd-216">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="691fd-216">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="691fd-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="691fd-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="691fd-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="691fd-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="691fd-219">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="691fd-219">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="691fd-220">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-220">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="691fd-221">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-221">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="691fd-222">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="691fd-222">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>