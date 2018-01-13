<Type Name="FabricClient+PropertyManagementClient" FullName="System.Fabric.FabricClient+PropertyManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/PropertyManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.PropertyManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.PropertyManagementClient = class" />
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
      <para><span data-ttu-id="218d8-101">名前およびプロパティの管理を実行するために使用するプロパティの管理クライアントを表します。</span><span class="sxs-lookup"><span data-stu-id="218d8-101">Represents the property management client used to perform management of names and properties.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync name" />
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
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-102">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-102">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-103">指定した Service Fabric 名前を作成します。</span><span class="sxs-lookup"><span data-stu-id="218d8-103">Creates the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-104">表す非同期のタスクは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="218d8-104">A task that represents the asynchronous create operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-105">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-105">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-106">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-106">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-107">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-107">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-108">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-108">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-109">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-109">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="218d8-110"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />サービス ファブリック名は既に存在する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-110"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" /> is returned when the Service Fabric name already exists.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-111">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-111">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-112">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-112">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-113">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-113">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-114">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-114">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-115">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-115">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-117">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-117">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-118">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-118">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync (name, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-119">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-119">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-120">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-120">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-121"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-121">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-122">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-122">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-123">指定した Service Fabric 名前を作成します。</span><span class="sxs-lookup"><span data-stu-id="218d8-123">Creates the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-124">表す非同期のタスクは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="218d8-124">A task that represents the asynchronous create operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-125">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-125">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-126">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-126">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-127">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-127">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-128">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-128">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-129">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-129">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="218d8-130"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />サービス ファブリック名は既に存在する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-130"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" /> is returned when the Service Fabric name already exists.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-131">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-131">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-132">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-132">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-133">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-133">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-134">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-134">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-135">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-135">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-136"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-136"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-137">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-137">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-138">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-138">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync name" />
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
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-139">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-139">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-140">指定したサービス ファブリック名を削除します。</span><span class="sxs-lookup"><span data-stu-id="218d8-140">Deletes the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-141">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-141">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-142">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-142">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-143">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-143">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-144">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-144">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-145">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-145">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-146">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-146">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-147">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-147">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-148"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-148"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-149">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-149">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-150">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-150">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-151">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-151">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-152">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-152">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-153">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-153">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-154"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-154"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-155"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />ときに返される<paramref name="name" />が他の名前、プロパティまたはサービスの親であります。</span><span class="sxs-lookup"><span data-stu-id="218d8-155"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" /> is returned when <paramref name="name" /> is parent of other Names, Properties or a Service.</span></span></para>
          <para>
                <span data-ttu-id="218d8-156">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-156">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-157">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-157">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync (name, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-158">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-158">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-159">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-159">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-160"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-160">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-161">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-161">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-162">指定したサービス ファブリック名を削除します。</span><span class="sxs-lookup"><span data-stu-id="218d8-162">Deletes the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-163">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-163">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-164">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-164">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-165">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-165">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-166">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-166">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-167">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-167">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-168">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-168">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-169">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-169">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-170"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-170"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-171">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-171">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-172">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-172">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-173">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-173">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-174">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-174">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-175">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-175">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-176"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-176"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-177"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />ときに返される<paramref name="name" />が他の名前、プロパティまたはサービスの親であります。</span><span class="sxs-lookup"><span data-stu-id="218d8-177"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" /> is returned when <paramref name="name" /> is parent of other Names, Properties or a Service.</span></span></para>
          <para>
                <span data-ttu-id="218d8-178">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-178">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-179">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-179">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePropertyAsync (parentName As Uri, propertyName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-180">プロパティの親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-180">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-181">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-181">The name of the Service Fabric property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-182">指定した Service Fabric プロパティを削除します。</span><span class="sxs-lookup"><span data-stu-id="218d8-182">Deletes the specified Service Fabric property.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-183">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-183">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-184">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-184">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-185">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-185">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-186">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-186">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-187">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-187">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-188">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-188">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-189">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-189">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-190"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-190"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-191"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-191"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-192">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-192">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-193"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-193"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-194">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-194">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-195">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-195">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-196">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-196">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-197">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-197">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-198">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-198">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-199"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-199"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-200">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-200">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-201">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-201">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-202">URI では、プロパティの親サービス ファブリック名を定義します。</span><span class="sxs-lookup"><span data-stu-id="218d8-202">URI defines the parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-203">文字列は、Service Fabric プロパティの名前を定義します。</span><span class="sxs-lookup"><span data-stu-id="218d8-203">String defines the name of the Service Fabric property.</span></span></para>
        </param>
        <param name="timeout">
          <para>
            <span data-ttu-id="218d8-204"><see cref="T:System.TimeSpan" />時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-204"><see cref="T:System.TimeSpan" /> defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="218d8-205"><see cref="T:System.Threading.CancellationToken" />操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="218d8-205"><see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-206">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-206">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-207">指定した Service Fabric プロパティを削除します。</span><span class="sxs-lookup"><span data-stu-id="218d8-207">Deletes the specified Service Fabric property.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-208">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-208">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-209">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-209">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-210">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-210">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-211">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-211">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-212">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-212">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-213">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-213">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-214">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-214">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-215"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-215"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-216"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-216"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-217">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-217">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-218"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-218"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-219">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-219">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-220">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-220">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-221">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-221">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-222">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-222">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-223">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-223">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-225">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-225">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-226">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-226">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumeratePropertiesAsync (name As Uri, includeValues As Boolean, previousResult As PropertyEnumerationResult) As Task(Of PropertyEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-227">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-227">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="includeValues">
          <para>
            <span data-ttu-id="218d8-228"><languageKeyword>True</languageKeyword>場合は、メタデータを持つ値が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-228"><languageKeyword>True</languageKeyword> if values should be returned with the metadata.</span></span> <span data-ttu-id="218d8-229"><languageKeyword>False</languageKeyword> ; プロパティ メタデータのみを返す<languageKeyword>true</languageKeyword>プロパティのメタデータと値を返します。</span><span class="sxs-lookup"><span data-stu-id="218d8-229"><languageKeyword>False</languageKeyword> to return only property metadata; <languageKeyword>true</languageKeyword> to return property metadata and value.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="218d8-230">前の呼び出しのバッチの結果。</span><span class="sxs-lookup"><span data-stu-id="218d8-230">The batch result for the previous call.</span></span> <span data-ttu-id="218d8-231">かどうか、このフィールドの最初の呼び出し必要があります設定を null にします。</span><span class="sxs-lookup"><span data-stu-id="218d8-231">If this the first call, this field needs to be set to null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-232">指定した名前の下にあるすべての Service Fabric プロパティを列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-232">Enumerates all Service Fabric properties under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-233">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-233">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-234">場合<see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />が true の場合、この結果は次の入力として使用できます<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="218d8-234">If <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> is true, then this result can be used as input to the next <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> call.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-235">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-235">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-236">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-236">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-237">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-237">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-238">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-238">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-239">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-239">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-240">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-240">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-241"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-241"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-242">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-242">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-243">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-243">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-244">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-244">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-245">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-245">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-246">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-246">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-247"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-247"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="218d8-248">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-248">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-249">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-249">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-250">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-250">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="includeValues">
          <para>
            <span data-ttu-id="218d8-251"><languageKeyword>True</languageKeyword>場合は、メタデータ、値が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-251"><languageKeyword>True</languageKeyword> if the values should be returned with the metadata.</span></span>
                <span data-ttu-id="218d8-252"><languageKeyword>False</languageKeyword> ; プロパティ メタデータのみを返す戻り値のプロパティのメタデータと値の場合は true です。</span><span class="sxs-lookup"><span data-stu-id="218d8-252"><languageKeyword>False</languageKeyword> to return only property metadata; true to return property metadata and value.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="218d8-253">前の呼び出しのバッチの結果。</span><span class="sxs-lookup"><span data-stu-id="218d8-253">The batch result for the previous call.</span></span> <span data-ttu-id="218d8-254">かどうか、このフィールドの最初の呼び出し必要があります設定を null にします。</span><span class="sxs-lookup"><span data-stu-id="218d8-254">If this the first call, this field needs to be set to null.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-255">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-255">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-256"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-256">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-257">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-257">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-258">指定した名前の下にあるすべての Service Fabric プロパティを列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-258">Enumerates all Service Fabric properties under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-259">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-259">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-260">場合<see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />が true の場合、この結果は次の入力として使用できます<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="218d8-260">If <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> is true, then this result can be used as input to the next <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> call.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-261">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-261">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-262">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-262">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-263">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-263">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-264">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-264">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-265">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-265">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-266">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-266">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-267"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-267"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-268">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-268">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-269">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-269">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-270">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-270">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-271">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-271">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-272">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-272">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-273"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-273"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="218d8-274">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-274">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-275">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-275">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateSubNamesAsync (name As Uri, previousResult As NameEnumerationResult, recursive As Boolean) As Task(Of NameEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-276">列挙する親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-276">The parent Service Fabric name to be enumerated.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="218d8-277">列挙の前の呼び出しによって返された結果。</span><span class="sxs-lookup"><span data-stu-id="218d8-277">The result that was returned by the previous enumerate call.</span></span> <span data-ttu-id="218d8-278">最初の呼び出しでは、これは null です。</span><span class="sxs-lookup"><span data-stu-id="218d8-278">For the initial call, this is null.</span></span></para>
        </param>
        <param name="recursive">
          <para>
            <span data-ttu-id="218d8-279"><languageKeyword>True</languageKeyword>列挙体は再帰的なをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="218d8-279"><languageKeyword>True</languageKeyword> the enumeration should be recursive.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-280">指定した名前の下のすべての Service Fabric 名を列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-280">Enumerates all the Service Fabric names under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-281">表す非同期のタスクは、操作を列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-281">A task that represents the asynchronous enumerate operation.</span></span></para>
          <para><span data-ttu-id="218d8-282">以下を参照してください。<see cref="T:System.Fabric.NameEnumerationResult" /></span><span class="sxs-lookup"><span data-stu-id="218d8-282">See <see cref="T:System.Fabric.NameEnumerationResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-283">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-283">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-284">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-284">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-285">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-285">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-286">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-286">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-287">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-287">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="218d8-288"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-288"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-289">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-289">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-290">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-290">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-291">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-291">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-292">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-292">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-293">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-293">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-294"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-294"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-295">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-295">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-296">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-296">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-297">列挙する親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-297">The parent Service Fabric name to be enumerated.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="218d8-298">列挙の前の呼び出しによって返された結果。</span><span class="sxs-lookup"><span data-stu-id="218d8-298">The result that was returned by the previous enumerate call.</span></span> <span data-ttu-id="218d8-299">最初の呼び出しでは、これは null です。</span><span class="sxs-lookup"><span data-stu-id="218d8-299">For the initial call, this is null.</span></span></para>
        </param>
        <param name="recursive">
          <para>
            <span data-ttu-id="218d8-300"><languageKeyword>True</languageKeyword>場合は、列挙体は再帰的なをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="218d8-300"><languageKeyword>True</languageKeyword> if the enumeration should be recursive.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-301">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-301">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-302"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-302">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-303">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-303">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-304">指定した名前の下のすべての Service Fabric 名を列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-304">Enumerates all the Service Fabric names under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-305">表す非同期のタスクは、操作を列挙します。</span><span class="sxs-lookup"><span data-stu-id="218d8-305">A task that represents the asynchronous enumerate operation.</span></span></para>
          <para><span data-ttu-id="218d8-306">以下を参照してください。<see cref="T:System.Fabric.NameEnumerationResult" /></span><span class="sxs-lookup"><span data-stu-id="218d8-306">See <see cref="T:System.Fabric.NameEnumerationResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-307">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-307">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-308">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-308">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-309">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-309">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-310">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-310">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-311">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-311">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="218d8-312"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-312"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-313">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-313">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-314">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-314">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-315">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-315">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-316">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-316">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-317">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-317">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-318"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-318"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-319">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-319">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-320">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-320">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyAsync (parentName As Uri, propertyName As String) As Task(Of NamedProperty)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-321">プロパティの親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-321">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-322">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-322">The name of the Service Fabric property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-323">指定した <see cref="T:System.Fabric.NamedProperty" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="218d8-323">Gets the specified <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-324">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-324">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-325">以下を参照してください。<see cref="T:System.Fabric.NamedProperty" /></span><span class="sxs-lookup"><span data-stu-id="218d8-325">See <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-326">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-326">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-327">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-327">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-328">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-328">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-329">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-329">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-330">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-330">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-331">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-331">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-332"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-332"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-333"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-333"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-334">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-334">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-335">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-335">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-336">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-336">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-337">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-337">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-338">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-338">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-339"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-339"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-340">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-340">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-341">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-341">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-342">プロパティの親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-342">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-343">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-343">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-344">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-344">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-345"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-345">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-346">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-346">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-347">指定した <see cref="T:System.Fabric.NamedProperty" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="218d8-347">Gets the specified <see cref="T:System.Fabric.NamedProperty" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-348">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-348">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-349">以下を参照してください。<see cref="T:System.Fabric.NamedProperty" /></span><span class="sxs-lookup"><span data-stu-id="218d8-349">See <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-350">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-350">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-351">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-351">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-352">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-352">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-353">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-353">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-354">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-354">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-355">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-355">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-356"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-356"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-357"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-357"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-358">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-358">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-359">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-359">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-360">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-360">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-361">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-361">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-362">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-362">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-363"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-363"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-364">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-364">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-365">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-365">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyMetadataAsync (parentName As Uri, propertyName As String) As Task(Of NamedPropertyMetadata)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-366">プロパティの親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-366">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-367">プロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-367">The name of the Property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-368">指定した <see cref="T:System.Fabric.NamedPropertyMetadata" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="218d8-368">Gets the specified <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-369">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-369">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-370">以下を参照してください。<see cref="T:System.Fabric.NamedPropertyMetadata" /></span><span class="sxs-lookup"><span data-stu-id="218d8-370">See <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-371">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-371">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-372">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-372">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-373">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-373">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-374">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-374">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-375">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-375">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-376">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-376">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-377"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-377"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-378"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-378"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-379">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-379">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-380">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-380">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-381">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-381">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-382">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-382">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-383">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-383">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-384"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-384"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-385">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-385">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-386">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-386">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-387">プロパティの親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-387">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-388">プロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-388">The name of the Property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-389">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-389">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-390"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-390">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="218d8-391">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-391">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-392">指定した <see cref="T:System.Fabric.NamedPropertyMetadata" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="218d8-392">Gets the specified <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-393">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-393">A task that represents the asynchronous get operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-394">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-394">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-395">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-395">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-396">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-396">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-397">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-397">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-398">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-398">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-399">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-399">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-400"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-400"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="218d8-401"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-401"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-402">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-402">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-403">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-403">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-404">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-404">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-405">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-405">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-406">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-406">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="218d8-408">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-408">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-409">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-409">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function NameExistsAsync (name As Uri) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-410">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-410">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-411">返します<languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="218d8-411">Returns <languageKeyword>true</languageKeyword> if the specified Service Fabric name exists.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-412">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-412">A task that represents the asynchronous operation.</span></span></para>
          <para>
            <span data-ttu-id="218d8-413"><languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="218d8-413"><languageKeyword>true</languageKeyword> if the specified Service Fabric name exists; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-414">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-414">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
          <para>
            <span data-ttu-id="218d8-415"><see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />クラスターを検証する方法の 1 つはおよび<see cref="T:System.Fabric.FabricClient" />クラスターに接続できます。</span><span class="sxs-lookup"><span data-stu-id="218d8-415"><see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> is the one way of verifying the cluster is up and <see cref="T:System.Fabric.FabricClient" /> can connect to the cluster.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-416">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-416">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-417">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-417">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-418">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-418">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-419">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-419">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-420">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-420">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-421">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-421">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-422">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-422">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-423">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-423">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-424">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-424">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-425"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-425"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-426">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-426">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-427">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-427">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-428">Service Fabric 名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-428">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-429">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-429">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-430"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-430">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-431">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-431">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-432">返します<languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="218d8-432">Returns <languageKeyword>true</languageKeyword> if the specified Service Fabric name exists.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-433">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-433">A task that represents the asynchronous operation.</span></span></para>
          <para>
            <span data-ttu-id="218d8-434"><languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="218d8-434"><languageKeyword>true</languageKeyword> if the specified Service Fabric name exists; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-435">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-435">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-436">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-436">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-437">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-437">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-438">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-438">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-439">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-439">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-440">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-440">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-441">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-441">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-442">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-442">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-443">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-443">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="218d8-445">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-445">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-446">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-446">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutCustomPropertyOperationAsync (name As Uri, operation As PutCustomPropertyOperation) As Task" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation)" />
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
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-447">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-447">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="operation">
          <para><span data-ttu-id="218d8-448">Put 操作パラメーターは、プロパティ名、値、およびカスタム型の情報を含むです。</span><span class="sxs-lookup"><span data-stu-id="218d8-448">The put operation parameters, including property name, value and custom type information.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-449">作成または更新によって記述された指定の Service Fabric プロパティ<see cref="T:System.Fabric.PutCustomPropertyOperation" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-449">Creates or updates the specified Service Fabric property described by <see cref="T:System.Fabric.PutCustomPropertyOperation" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-450">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-450">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-451">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-451">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-452">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-452">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-453">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-453">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-454">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-454">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-455">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-455">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-456"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-456"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-457">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-457">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-458"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-458"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-459">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-459">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-460">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-460">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-461">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-461">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-462">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-462">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-463">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-463">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-465"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-465"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-466">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-466">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-467">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-467">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation, timeout, cancellationToken)" />
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
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="218d8-468">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-468">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="operation">
          <para><span data-ttu-id="218d8-469">Put 操作パラメーターは、プロパティ名、値、およびカスタム型の情報を含むです。</span><span class="sxs-lookup"><span data-stu-id="218d8-469">The put operation parameters, including property name, value and custom type information.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-470">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-470">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-471"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-471">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="218d8-472">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-472">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-473">作成または更新によって記述された指定の Service Fabric プロパティ<see cref="T:System.Fabric.PutCustomPropertyOperation" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-473">Creates or updates the specified Service Fabric property described by <see cref="T:System.Fabric.PutCustomPropertyOperation" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-474">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-474">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-475">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-475">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-476">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-476">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-477">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-477">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-478">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-478">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-479">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-479">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-480"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="name" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-480"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-481">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-481">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-482"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-482"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-483">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-483">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-484">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-484">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-485">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-485">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-486">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-486">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-487">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-487">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-488"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-488"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-489"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-489"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-490">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-490">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-491">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-491">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-492">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-492">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-493">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-493">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-494">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-494">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-495">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Byte" />は指定された名前の配列。</span><span class="sxs-lookup"><span data-stu-id="218d8-495">Creates or updates the specified Service Fabric property of type <see cref="T:System.Byte" /> array under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-496">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-496">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-497">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-497">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-498">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-498">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-499">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-499">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-500">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-500">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-501">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-501">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-502">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-502">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-503"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-503"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-504">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-504">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-505"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-505"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-506">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-506">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-507">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-507">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-508">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-508">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-509">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-509">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-510">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-510">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-511"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-511"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-512"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-512"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-513">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-513">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-514">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-514">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Double) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-515">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-515">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-516">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-516">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-517">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-517">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-518">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Double" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-518">Creates or updates the specified Service Fabric property of type <see cref="T:System.Double" /> under a given name.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-519">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-519">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-520">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-520">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-521">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-521">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-522">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-522">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-523">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-523">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-524">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-524">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-525">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-525">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-526"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-526"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-527">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-527">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-528"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-528"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-529">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-529">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-530">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-530">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-531">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-531">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-532">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-532">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-533">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-533">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-534"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-534"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-535"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-535"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-536">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-536">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-537">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-537">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-538">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-538">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-539">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-539">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-540">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-540">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-541">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Guid" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-541">Creates or updates the specified Service Fabric property of type <see cref="T:System.Guid" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-542">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-542">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-543">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-543">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-544">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-544">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-545">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-545">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-546">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-546">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-547">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-547">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-548">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-548">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-549"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-549"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-550">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-550">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-551"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-551"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-552">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-552">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-553">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-553">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-554">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-554">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-555">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-555">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-556">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-556">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-558"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-558"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-559">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-559">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-560">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-560">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-561">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-561">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-562">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-562">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-563">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-563">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-564">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Int64" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-564">Creates or updates the specified Service Fabric property of type <see cref="T:System.Int64" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-565">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-565">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-566">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-566">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-567">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-567">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-568">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-568">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-569">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-569">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-570">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-570">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-571">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-571">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-572"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-572"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-573">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-573">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-574"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-574"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-575">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-575">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-576">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-576">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-577">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-577">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-578">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-578">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-579">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-579">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-580"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-580"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-581"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-581"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-582">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-582">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-583">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-583">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As String) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-584">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-584">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-585">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-585">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-586">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-586">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-587">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.String" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-587">Creates or updates the specified Service Fabric property of type <see cref="T:System.String" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-588">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-588">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-589">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-589">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-590">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-590">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-591">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-591">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-592">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-592">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-593">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-593">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-594">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-594">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-595"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-595"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-596">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-596">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-597"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-597"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-598">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-598">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-599">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-599">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-600">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-600">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-601">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-601">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-602">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-602">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-603"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-603"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-604"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-604"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-605">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-605">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-606">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-606">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-607">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-607">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-608">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-608">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-609">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-609">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-610">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-610">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-611"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-611">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="218d8-612">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-612">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-613">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Byte" />は指定された名前の配列。</span><span class="sxs-lookup"><span data-stu-id="218d8-613">Creates or updates the specified Service Fabric property of type <see cref="T:System.Byte" /> array under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-614">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-614">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-615">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-615">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-616">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-616">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-617">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-617">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-618">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-618">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-619">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-619">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-620">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-620">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-621"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-621"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-622">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-622">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-623"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-623"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-624">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-624">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-625">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-625">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-626">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-626">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-627">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-627">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-628">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-628">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-629"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-629"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-630"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-630"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-631">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-631">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-632">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-632">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-633">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-633">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-634">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-634">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-635">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-635">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-636">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-636">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-637"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-637">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-638">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-638">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-639">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Double" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-639">Creates or updates the specified Service Fabric property of type <see cref="T:System.Double" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-640">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-640">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-641">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-641">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-642">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-642">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-643">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-643">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-644">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-644">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-645">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-645">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-646">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-646">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-647"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-647"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-648">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-648">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-649"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-649"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-650">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-650">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-651">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-651">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-652">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-652">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-653">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-653">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-654">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-654">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-655"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-655"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-656"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-656"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-657">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-657">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-658">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-658">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-659">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-659">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-660">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-660">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-661">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-661">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-662">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-662">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-663"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-663">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="218d8-664">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-664">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-665">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Guid" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-665">Creates or updates the specified Service Fabric property of type <see cref="T:System.Guid" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-666">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-666">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-667">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-667">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-668">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-668">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-669">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-669">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-670">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-670">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-671">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-671">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-672">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-672">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-673"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-673"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-674">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-674">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-675"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-675"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-676">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-676">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-677">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-677">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-678">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-678">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-679">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-679">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-680">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-680">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-681"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-681"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-682"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-682"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-683">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-683">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-684">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-684">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-685">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-685">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-686">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-686">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-687">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-687">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-688">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-688">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-689"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-689">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-690">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-690">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-691">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Int64" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-691">Creates or updates the specified Service Fabric property of type <see cref="T:System.Int64" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-692">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-692">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-693">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-693">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-694">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-694">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-695">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-695">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-696">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-696">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-697">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-697">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-698">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-698">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-699"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-699"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-700">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-700">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-701"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-701"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-702">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-702">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-703">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-703">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-704">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-704">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-705">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-705">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-706">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-706">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-708"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-708"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-709">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-709">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-710">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-710">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-711">親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-711">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="218d8-712">Service Fabric プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="218d8-712">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="218d8-713">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="218d8-713">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-714">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-714">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-715">操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="218d8-715">The operation is observing.</span></span> <span data-ttu-id="218d8-716">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-716">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-717">作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.String" />下にある指定された名前です。</span><span class="sxs-lookup"><span data-stu-id="218d8-717">Creates or updates the specified Service Fabric property of type <see cref="T:System.String" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-718">表す非同期のタスクは、操作を配置します。</span><span class="sxs-lookup"><span data-stu-id="218d8-718">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-719">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-719">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-720">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-720">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-721">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-721">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-722">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-722">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-723">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-723">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-724">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-724">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-725"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-725"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-726">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-726">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-727"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-727"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-728">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-728">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-729">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-729">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-730">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-730">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-731">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-731">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-732">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-732">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-734"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</span><span class="sxs-lookup"><span data-stu-id="218d8-734"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="218d8-735">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-735">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-736">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-736">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitPropertyBatchAsync (parentName As Uri, operations As ICollection(Of PropertyBatchOperation)) As Task(Of PropertyBatchResult)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-737">プロパティ バッチ操作を実行する親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-737">The parent Service Fabric name under which the Property batch operations will be executed.</span></span></para>
        </param>
        <param name="operations">
          <para><span data-ttu-id="218d8-738">バッチ プロパティ操作です。</span><span class="sxs-lookup"><span data-stu-id="218d8-738">The batch property operations.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-739">バッチ送信<see cref="T:System.Fabric.PropertyBatchOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-739">Submits a batch of <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-740">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-740">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-741">以下を参照してください。<see cref="T:System.Fabric.PropertyBatchResult" /></span><span class="sxs-lookup"><span data-stu-id="218d8-741">See <see cref="T:System.Fabric.PropertyBatchResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-742">いずれかまたはすべてのバッチ内の操作がコミットされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-742">Either all or none of the operations in the batch will be committed.</span></span> </para>
          <para><span data-ttu-id="218d8-743">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-743">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-744">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-744">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-745">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-745">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-746">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-746">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-747">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-747">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-748">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-748">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-749"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-749"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-750">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-750">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-751"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-751"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-752">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-752">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-753">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-753">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-754">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-754">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-755">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-755">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-756">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-756">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-757"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-757"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-758"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />プロパティ値が 1 MB より大きい場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-758"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when property value is larger than 1MB.</span></span></para>
          <para>
            <span data-ttu-id="218d8-759"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />少なくとも 1 つチェック操作のユーザーに提供されている場合に返される<paramref name="operations" />に失敗しました。</span><span class="sxs-lookup"><span data-stu-id="218d8-759"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" /> is returned when at least one check operation in the user provided <paramref name="operations" /> has failed.</span></span></para>
          <para>
                <span data-ttu-id="218d8-760">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-760">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-761">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-761">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="218d8-762">プロパティ バッチ操作を実行する親サービス ファブリック名。</span><span class="sxs-lookup"><span data-stu-id="218d8-762">The parent Service Fabric name under which the Property batch operations will be executed.</span></span></para>
        </param>
        <param name="operations">
          <para><span data-ttu-id="218d8-763">バッチ プロパティ操作です。</span><span class="sxs-lookup"><span data-stu-id="218d8-763">The batch property operations.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="218d8-764">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="218d8-764">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="218d8-765"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="218d8-765">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="218d8-766">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="218d8-766">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="218d8-767">バッチ送信<see cref="T:System.Fabric.PropertyBatchOperation" />s。</span><span class="sxs-lookup"><span data-stu-id="218d8-767">Submits a batch of <see cref="T:System.Fabric.PropertyBatchOperation" />s.</span></span> <span data-ttu-id="218d8-768">いずれかまたはすべてのバッチ内の操作がコミットされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-768">Either all or none of the operations in the batch will be committed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="218d8-769">非同期の get 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="218d8-769">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="218d8-770">以下を参照してください。<see cref="T:System.Fabric.PropertyBatchResult" /></span><span class="sxs-lookup"><span data-stu-id="218d8-770">See <see cref="T:System.Fabric.PropertyBatchResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="218d8-771">いずれかまたはすべてのバッチ内の操作がコミットされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-771">Either all or none of the operations in the batch will be committed.</span></span> </para>
          <para><span data-ttu-id="218d8-772">操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-772">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="218d8-773">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-773">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-774">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-774">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="218d8-775">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-775">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-776">Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</span><span class="sxs-lookup"><span data-stu-id="218d8-776">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="218d8-777">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-777">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-778"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</span><span class="sxs-lookup"><span data-stu-id="218d8-778"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="218d8-779">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-779">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-780"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-780"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="218d8-781">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-781">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="218d8-782">操作が中止されました E_ABORT が返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-782">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="218d8-783">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-783">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="218d8-784">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-784">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="218d8-785">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="218d8-785">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="218d8-786"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</span><span class="sxs-lookup"><span data-stu-id="218d8-786"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="218d8-787"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />プロパティ値が 1 MB より大きい場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="218d8-787"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when property value is larger than 1MB.</span></span></para>
          <para>
            <span data-ttu-id="218d8-788"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />少なくとも 1 つチェック操作のユーザーに提供されている場合に返される<paramref name="operations" />に失敗しました。</span><span class="sxs-lookup"><span data-stu-id="218d8-788"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" /> is returned when at least one check operation in the user provided <paramref name="operations" /> has failed.</span></span></para>
          <para>
                <span data-ttu-id="218d8-789">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="218d8-789">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="218d8-790">内部エラーが発生した場合は、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="218d8-790">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>