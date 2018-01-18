<Type Name="FabricClient+HealthClient" FullName="System.Fabric.FabricClient+HealthClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.HealthClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/HealthClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.HealthClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.HealthClient" />
  <TypeSignature Language="F#" Value="type FabricClient.HealthClient = class" />
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
      <para><span data-ttu-id="4c57b-101">正常性を実行する機能を提供に関連するレポートおよびクエリの状態と同様に、操作します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-101">Provides functionality to perform health related operations, like report and query health.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (queryDescription As ApplicationHealthQueryDescription) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-102"><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />アプリケーションの正常性を取得するクエリを記述するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="4c57b-102">The <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> instance to describe the query to get application health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-103">指定されたクエリの説明を使用して、指定した Service Fabric アプリケーションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-103">Asynchronously gets the health of the specified Service Fabric application by using the specified query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-104">指定した Service Fabric アプリケーションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-104">The health of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-105"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-105">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-106">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-106">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-107">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-107">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-108">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-108">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-109">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-109">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-110">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-110">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-111"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-111"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-112">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-112">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-113"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-113"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-114"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-114"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-115"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-115"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-119"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-119"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-121"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-121"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-122"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-122"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-123"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-123"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-124"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-124"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-125">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-125">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-126"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-126"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-127">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-127">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-128">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-128">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-129">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-129">The URI of the Service Fabric application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-130">指定した Service Fabric アプリケーションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-130">Asynchronously gets the health of the specified Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-131">指定した Service Fabric アプリケーションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-131">The health of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-132">次の例では、アプリケーションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-132">The following example gets the health of an application.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-133">パブリック静的 bool GetApplicationHealth(string clusterConnection) {ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-133">public static bool GetApplicationHealth(string clusterConnection) { ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="4c57b-134">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-134">// Connect to the cluster.</span></span>
                <span data-ttu-id="4c57b-135">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-135">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
            
                <span data-ttu-id="4c57b-136">アプリケーションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-136">// Get the application health.</span></span>
                <span data-ttu-id="4c57b-137">再試行してください {applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-137">try { applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
                <span data-ttu-id="4c57b-138">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-138">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="4c57b-139">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-139">return false; }</span></span>
                    
                <span data-ttu-id="4c57b-140">アプリケーションの正常性の情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-140">// Display the application health information.</span></span>
                <span data-ttu-id="4c57b-141">Console.WriteLine ("アプリケーションの正常性の取得:") です。Console.WriteLine ("アプリケーション {0}: {1}"、applicationHealth.ApplicationName、applicationHealth.AggregatedHealthState) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-141">Console.WriteLine("Get Application Health:"); Console.WriteLine("  Application {0}: {1}", applicationHealth.ApplicationName, applicationHealth.AggregatedHealthState);</span></span>
                
                    <span data-ttu-id="4c57b-142">展開済みアプリケーションのヘルス状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-142">// List the deployed application health states.</span></span>
            <span data-ttu-id="4c57b-143">Console.WriteLine ("配置済みのアプリケーション:") です。IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState でdeployedAppHealthStateList) {Console.WriteLine ("アプリケーション:"+ deployedAppHealthState.ApplicationName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedAppHealthState.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedAppHealthState.NodeName);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-143">Console.WriteLine("    Deployed applications:"); IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState in deployedAppHealthStateList) { Console.WriteLine("      Application: " + deployedAppHealthState.ApplicationName); Console.WriteLine("        Aggregated Health State: " + deployedAppHealthState.AggregatedHealthState); Console.WriteLine("        Node Name: " + deployedAppHealthState.NodeName); }</span></span>
                    
            <span data-ttu-id="4c57b-144">デプロイ済みサービスのヘルス状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-144">// List the deployed services health states.</span></span>
            <span data-ttu-id="4c57b-145">Console.WriteLine ("サービスの正常性状態:") です。IList&lt;ServiceHealthState&gt; deployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; foreach (deployedSvcsHealthStateList で ServiceHealthState serviceHealthState) {Console.WriteLine ("サービス {0}: {1}"、serviceHealthState.ServiceName、serviceHealthState.AggregatedHealthState) です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-145">Console.WriteLine("    Service Health States:"); IList&lt;ServiceHealthState&gt; deployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; foreach (ServiceHealthState serviceHealthState in deployedSvcsHealthStateList) { Console.WriteLine("      Service {0}: {1}", serviceHealthState.ServiceName, serviceHealthState.AggregatedHealthState); }</span></span>
                    
                <span data-ttu-id="4c57b-146">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-146">// List the health events.</span></span>
            <span data-ttu-id="4c57b-147">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = applicationHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-147">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = applicationHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                
                <span data-ttu-id="4c57b-148">Console.WriteLine() です。true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-148">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-149"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-149">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-150">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-150">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-151">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-151">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-152">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-152">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-153"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-153"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-154">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-154">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-155"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-155"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-156"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-156"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-157"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-157"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-159"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-159"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-160"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-160"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-161"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-161"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-162"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-162"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-163"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-163"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-164"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-164"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-165"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-165"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-166"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-166"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-167">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-167">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-168"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-168"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-169">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-169">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-170">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-170">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-171">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-171">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-172"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />インスタンス アプリケーションを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-172">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> instance used to evaluate the application.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-173">非同期的に、アプリケーション URI と正常性ポリシーを使用して、指定した Service Fabric アプリケーションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-173">Asynchronously gets the health of the specified Service Fabric application using the application URI and the health policy.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-174">指定した Service Fabric アプリケーションの正常性レポートします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-174">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-175"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-175">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-176">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-176">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-177">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-177">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-178">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-178">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-179">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-179">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-180">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-180">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-181"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-181"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-182">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-182">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-183"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-183"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-184"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-184"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-185"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-185"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-186"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-186"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-188"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-188"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-190"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-190"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-191"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-191"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-192"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-192"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-193"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-193"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-194"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-194"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-195">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-195">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-196"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-196"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-197">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-197">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-198">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-198">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-199"><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />アプリケーションの正常性を取得するクエリを記述するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="4c57b-199">The <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> instance to describe the query to get application health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-200">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-200">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-201">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-201">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-202">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-202">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-203">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-203">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-204">非同期的に指定されたクエリの入力、タイムアウトおよび取り消しを使用して、指定した Service Fabric アプリケーションの正常性をトークンの取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-204">Asynchronously gets the health of the specified Service Fabric application using the specified query input, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-205">指定した Service Fabric アプリケーションの正常性レポートします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-205">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-206"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-206">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-207">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-207">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-208">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-208">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-209">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-209">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-210">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-210">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-211">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-211">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-212"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-212"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-213">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-213">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-214"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-214"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-215"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-215"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-216"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-216"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-217"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-217"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-218"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-218"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-219"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-219"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-220"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-220"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-221"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-221"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-222"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-222"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-223"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-223"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-225"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-225"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-226">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-226">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-227"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-227"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-228">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-228">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-229">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-229">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-230">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-230">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-231">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-231">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-232">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-232">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-233">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-233">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-234">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-234">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-235">トークン、指定したアプリケーション URI、タイムアウトや取り消しを使用して、指定した Service Fabric アプリケーションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-235">Asynchronously gets the health of the specified Service Fabric application using the specified application URI, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-236">指定した Service Fabric アプリケーションの正常性レポートします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-236">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-237"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-237">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-238">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-238">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-239">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-239">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-240">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-240">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-241">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-241">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-242">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-242">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-243"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-243"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-244">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-244">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-245"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-245"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-246"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-246"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-247"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-247"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-248"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-248"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-249"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-249"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-250"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-250"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-251"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-251"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-252"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-252"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-253"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-253"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-254"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-254"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-255"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-255"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-256"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-256"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-257">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-257">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-258"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-258"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-259">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-259">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-260">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-260">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-261">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-261">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-262">アプリケーションの正常性ポリシーはアプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-262">The application health policy used to evaluate the application health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-263">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-263">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-264">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-264">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-265">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-265">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-266">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-266">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-267">非同期的に、指定した Service Fabric アプリケーションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-267">Asynchronously gets the health of the specified Service Fabric application by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-268">指定した Service Fabric アプリケーションの正常性レポートします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-268">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-269"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-269">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-270">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-270">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-271">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-271">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-272">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-272">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-273">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-273">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-274">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-274">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-275"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-275"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-276">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-276">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-277"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-277"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-278"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-278"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-279"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-279"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-280"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-280"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-281"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-281"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-282"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-282"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-283"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-283"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-284"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-284"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-285"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-285"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-286"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-286"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-287"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-287"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-288"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-288"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-289">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-289">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-290"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-290"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-291">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-291">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-292">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-292">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync () As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4c57b-293">Service Fabric クラスターの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-293">Asynchronously gets the health of a Service Fabric cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-294">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-294">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-295">次の例では、クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-295">The following example gets the health of the cluster.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-296">パブリック静的 bool GetClusterHealth(string clusterConnection) {ClusterHealth clusterHealth です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-296">public static bool GetClusterHealth(string clusterConnection) { ClusterHealth clusterHealth;</span></span>
            
                <span data-ttu-id="4c57b-297">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-297">// Connect to the cluster.</span></span>
            <span data-ttu-id="4c57b-298">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-298">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="4c57b-299">クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-299">// Get the cluster health.</span></span>
            <span data-ttu-id="4c57b-300">再試行してください {clusterHealth fabricClient.HealthManager.GetClusterHealthAsync() を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-300">try { clusterHealth = fabricClient.HealthManager.GetClusterHealthAsync().Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="4c57b-301">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-301">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="4c57b-302">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-302">return false; }</span></span>
                
                <span data-ttu-id="4c57b-303">クラスターの正常性状態を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-303">// Display the cluster health state.</span></span>
                <span data-ttu-id="4c57b-304">Console.WriteLine ("クラスターの正常性:") です。Console.WriteLine ("ヘルス状態を集計します。"+ clusterHealth.AggregatedHealthState) です。Console.WriteLine() です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-304">Console.WriteLine("Cluster Health:"); Console.WriteLine("  Aggregated Health State: " + clusterHealth.AggregatedHealthState); Console.WriteLine();</span></span>
                    
            <span data-ttu-id="4c57b-305">クラスター上のアプリケーションのヘルス状態を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-305">// Display the application health states on the cluster.</span></span>
                    <span data-ttu-id="4c57b-306">Console.WriteLine ("アプリケーションの正常性状態:") です。IList&lt;ApplicationHealthState&gt; applicationHealthStateList = clusterHealth.ApplicationHealthStates; foreach (applicationHealthStateList で ApplicationHealthState applicationHealthState) {Console.WriteLine ("   アプリケーション {0}: {1}"、applicationHealthState.ApplicationName、applicationHealthState.AggregatedHealthState) です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-306">Console.WriteLine("  Application Health States:"); IList&lt;ApplicationHealthState&gt; applicationHealthStateList = clusterHealth.ApplicationHealthStates; foreach(ApplicationHealthState applicationHealthState in applicationHealthStateList) { Console.WriteLine("    Application {0}: {1}", applicationHealthState.ApplicationName, applicationHealthState.AggregatedHealthState); }</span></span>
            
            <span data-ttu-id="4c57b-307">クラスター上には、ノード ヘルス状態を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-307">// Display Node Health States on the cluster.</span></span>
                    <span data-ttu-id="4c57b-308">Console.WriteLine ("ノードの正常性状態:") です。IList&lt;NodeHealthState&gt; nodeHealthStateList = clusterHealth.NodeHealthStates; foreach (nodeHealthStateList で NodeHealthState nodeHealthState) {Console.WriteLine ("ノード名:"+ nodeHealthState.NodeName) です。Console.WriteLine ("ヘルス状態を集計します"+ nodeHealthState.AggregatedHealthState);}。</span><span class="sxs-lookup"><span data-stu-id="4c57b-308">Console.WriteLine("  Node Health States:"); IList&lt;NodeHealthState&gt; nodeHealthStateList = clusterHealth.NodeHealthStates; foreach (NodeHealthState nodeHealthState in nodeHealthStateList) { Console.WriteLine("    Node Name: " + nodeHealthState.NodeName); Console.WriteLine("      Aggregated Health State: " + nodeHealthState.AggregatedHealthState); }</span></span>
                
            <span data-ttu-id="4c57b-309">正常性イベントを表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-309">// Display Health Events.</span></span>
                <span data-ttu-id="4c57b-310">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEventList = clusterHealth.HealthEvents; foreach (healthEventList で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-310">Console.WriteLine("  Health Events:"); IList&lt;HealthEvent&gt; healthEventList = clusterHealth.HealthEvents; foreach(HealthEvent healthEvent in healthEventList) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                
                <span data-ttu-id="4c57b-311">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = clusterHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-311">Console.WriteLine("  Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = clusterHealth.UnhealthyEvaluations; foreach(HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("    Kind: " + healthEvaluation.Kind); Console.WriteLine("      Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("      Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="4c57b-312">true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-312">return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-313"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-313">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-314">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-314">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-315">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-315">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-316">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-316">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-317">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-317">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-318">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-318">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-319"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-319"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-320">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-320">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-321"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-321"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-322"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-322"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-323"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-323"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-324"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-324"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-325"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-325"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-326"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-326"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-327"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-327"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-328"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-328"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-331"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-331"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-332">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-332">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-333"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-333"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-334">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-334">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-335">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-335">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (queryDescription As ClusterHealthQueryDescription) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-336">正常性ポリシーのようにクエリ パラメーターを定義するクエリの説明がなどにフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-336">The query description that defines query parameters like health policies, filters etc.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-337">非同期的にクエリの説明を使用して、Service Fabric クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-337">Asynchronously gets the health of a Service Fabric cluster by using a query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-338">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-338">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-339"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-339">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-340">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-340">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-341">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-341">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-342">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-342">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-343">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-343">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-344">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-344">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-345"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-345"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-346">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-346">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-347"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-347"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-348"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-348"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-349"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-349"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-351"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-351"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-352"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-352"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-353"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-353"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-354"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-354"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-355"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-355"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-356"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-356"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-357"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-357"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-358">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-358">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-359"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-359"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-360">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-360">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-361">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-361">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (healthPolicy As ClusterHealthPolicy) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync healthPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="healthPolicy"><span data-ttu-id="4c57b-362">クラスターの正常性ポリシーはクラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-362">The cluster health policy used to evaluate cluster health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-363">指定したポリシーを使用して評価する、Service Fabric クラスターの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-363">Asynchronously gets the health of a Service Fabric cluster, evaluating it using the specified policy.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-364">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-364">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-365"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-365">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-366">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-366">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-367">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-367">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-368">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-368">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-369">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-369">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-370">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-370">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-371"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-371"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-372">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-372">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-373"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-373"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-374"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-374"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-375"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-375"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-376"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-376"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-377"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-377"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-378"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-378"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-379"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-379"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-380"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-380"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-381"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-381"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-382"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-382"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-383"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-383"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-384">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-384">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-385"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-385"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-386">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-386">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-387">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-387">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-388">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-388">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-389">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-389">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-390">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-390">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-391">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-391">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-392">非同期的に Service Fabric クラスターの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-392">Asynchronously gets the health of a Service Fabric cluster by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-393">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-393">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-394"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-394">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-395">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-395">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-396">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-396">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-397">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-397">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-398">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-398">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-399">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-399">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-400"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-400"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-401">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-401">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-402"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-402"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-403"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-403"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-404"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-404"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-405"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-405"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-406"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-406"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-408"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-408"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-409"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-409"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-410"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-410"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-411"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-411"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-412"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-412"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-413">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-413">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-414"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-414"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-415">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-415">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-416">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-416">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-417">正常性ポリシーのようにクエリ パラメーターを定義するクエリの説明がなどにフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-417">The query description that defined query parameters like health policies, filters etc.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-418">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-418">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-419">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-419">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-420">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-420">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-421">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-421">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-422">非同期的に Service Fabric クラスターの正常性クエリの説明、タイムアウトおよび取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-422">Asynchronously gets the health of a Service Fabric cluster by using a query description, a timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-423">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-423">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-424"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-424">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-425">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-425">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-426">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-426">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-427">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-427">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-428">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-428">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-429">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-429">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-430"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-430"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-431">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-431">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-432"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-432"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-433"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-433"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-434"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-434"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-435"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-435"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-436"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-436"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-437"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-437"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-438"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-438"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-439"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-439"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-440"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-440"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-441"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-441"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-442"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-442"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-443">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-443">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-444"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-444"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-445">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-445">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-446">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-446">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="healthPolicy"><span data-ttu-id="4c57b-447">クラスターの正常性ポリシーはクラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-447">The cluster health policy used to evaluate cluster health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-448">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-448">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-449">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-449">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-450">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-450">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-451">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-451">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-452">非同期的に Service Fabric クラスターの正常性の指定した正常性ポリシー、タイムアウトと取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-452">Asynchronously gets the health of a Service Fabric cluster by using the specified health policy, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-453">Service Fabric クラスターの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-453">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-454"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-454">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-455">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-455">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-456">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-456">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-457">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-457">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-458">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-458">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-459">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-459">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-460"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-460"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-461">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-461">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-462"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-462"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-463"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-463"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-465"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-465"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-466"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-466"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-467"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-467"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-468"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-468"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-469"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-469"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-470"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-470"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-471"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-471"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-472"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-472"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-473">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-473">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-474"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-474"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-475">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-475">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-476">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-476">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync () As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c57b-477">Service Fabric クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-477">Gets the health of a Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="4c57b-478">クラスターの正常性を表すヘルス チャンクです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-478">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="4c57b-479">集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-479">The cluster aggregated health state is computed based on all entities in the cluster.</span></span>
            <span data-ttu-id="4c57b-480">コンソール アプリケーションは、フィルターが指定されていないため、結果で、子は含まれません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-480">No children are included in the results, because no filters are specified.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="4c57b-481">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-481">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="4c57b-482">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-482">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-483">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-483">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-484"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-484"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="4c57b-485">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-485">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-486">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-486">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-487"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-487"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-488">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-488">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-489">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-489">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync (queryDescription As ClusterHealthChunkQueryDescription) As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-490">正常性評価を実行する方法とにどのようなエンティティを含めるかを定義するクエリの説明、<see cref="T:System.Fabric.Health.ClusterHealthChunk" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-490">The query description that defines how health evaluation should be performed and what entities should be included in the <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span></span></param>
        <summary>
            <span data-ttu-id="4c57b-491">クエリの説明で要求されるとおり、クラスターのエンティティを含む、Service Fabric クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-491">Gets the health of a Service Fabric cluster, including cluster entities as requested in the query description.</span></span>
            </summary>
        <returns><span data-ttu-id="4c57b-492">クラスターの正常性を表すヘルス チャンクです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-492">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="4c57b-493">集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-493">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="4c57b-494">結果には、入力クエリの説明 (該当する場合) からのフィルターを適用する子のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="4c57b-494">Only the children that respect the filters from the input query description (if any) are included in the results.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="4c57b-495">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-495">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="4c57b-496">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-496">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-497">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-497">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-498"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-498"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="4c57b-499">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-499">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-500">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-500">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-501">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-501">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-502">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-502">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-503">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-503">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-504"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-504"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-505">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-505">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-506">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-506">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="4c57b-507">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-507">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4c57b-508">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-508">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-509">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-509">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-510">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-510">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></param>
        <summary>
            <span data-ttu-id="4c57b-511">Service Fabric クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-511">Gets the health of a Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="4c57b-512">クラスターの正常性を表すヘルス チャンクです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-512">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="4c57b-513">集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-513">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="4c57b-514">コンソール アプリケーションは、フィルターが指定されていないため、結果で、子は含まれません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-514">No children are included in the results, because no filters are specified.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="4c57b-515">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-515">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="4c57b-516">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-516">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-517">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-517">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-518"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-518"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="4c57b-519">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-519">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-520">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-520">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-521"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-521"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-522">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-522">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-523">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-523">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-524">正常性評価を実行する方法とにどのようなエンティティを含めるかを定義するクエリの説明、<see cref="T:System.Fabric.Health.ClusterHealthChunk" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-524">The query description that defines how health evaluation should be performed and what entities should be included in the <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="4c57b-525">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-525">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4c57b-526">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-526">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-527">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-527">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-528">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-528">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></param>
        <summary>
            <span data-ttu-id="4c57b-529">クエリの説明で要求されるとおり、クラスターのエンティティを含む、Service Fabric クラスターの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-529">Gets the health of a Service Fabric cluster, including cluster entities as requested in the query description.</span></span>
            </summary>
        <returns><span data-ttu-id="4c57b-530">クラスターの正常性を表すヘルス チャンクです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-530">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="4c57b-531">集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-531">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="4c57b-532">結果には、入力クエリの説明 (該当する場合) からのフィルターを適用する子のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="4c57b-532">Only the children that respect the filters from the input query description (if any) are included in the results.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="4c57b-533">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-533">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="4c57b-534">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-534">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-535">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-535">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-536"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-536"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="4c57b-537">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-537">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-538">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-538">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-539">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-539">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-540">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-540">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-541">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-541">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-542"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-542"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-543">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-543">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-544">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-544">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (queryDescription As DeployedApplicationHealthQueryDescription) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-545">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-545">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-546">非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-546">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-547">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4c57b-547">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-548"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-548">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-549">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-549">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-550">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-550">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-551">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-551">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-552">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-552">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-553">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-553">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-555">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-555">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-568">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-568">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-570">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-570">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-571">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-571">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-572">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-572">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-573">Service Fabric アプリケーションの配置先となるノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-573">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-574">指定されたノードで、展開済みの Service Fabric アプリケーションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-574">Asynchronously gets the health of a deployed Service Fabric application on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-575">展開済みの Service Fabric アプリケーションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-575">The health of a deployed Service Fabric application.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-576">次の例では、配置済みのアプリケーションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-576">The following example gets the health of a deployed application.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-577">パブリック静的 bool GetDeployedApplicationsHealth(string clusterConnection) {//DeployedApplicationHealth deployedApplicationHealth;//ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-577">public static bool GetDeployedApplicationsHealth(string clusterConnection) { //DeployedApplicationHealth deployedApplicationHealth; //ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="4c57b-578">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-578">// Connect to the cluster.</span></span>
                <span data-ttu-id="4c57b-579">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-579">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
            <span data-ttu-id="4c57b-580">Console.WriteLine ("アプリケーションの正常性を展開します。") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-580">Console.WriteLine("Deployed Application Health:");</span></span>
                
                <span data-ttu-id="4c57b-581">再試行してください {//アプリケーションが配置されているノードを決定します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-581">try { // Determine the nodes where the application has been deployed.</span></span>
            <span data-ttu-id="4c57b-582">ApplicationHealth applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-582">ApplicationHealth applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result;</span></span>
                
            <span data-ttu-id="4c57b-583">各ノードの展開済みアプリケーションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-583">// Get the deployed application health for each node.</span></span>
                <span data-ttu-id="4c57b-584">IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState でdeployedAppHealthStateList) {DeployedApplicationHealth deployedApplicationHealth fabricClient.HealthManager.GetDeployedApplicationHealthAsync (applicationName、deployedAppHealthState.NodeName) を = です。結果です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-584">IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState in deployedAppHealthStateList) { DeployedApplicationHealth deployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync(applicationName, deployedAppHealthState.NodeName).Result;</span></span>
                
                    <span data-ttu-id="4c57b-585">各ノードの展開済みアプリケーションのヘルス情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-585">// Display the deployed application health information for each node.</span></span>
                    
            <span data-ttu-id="4c57b-586">Console.WriteLine ("アプリケーション {0}: {1}"、deployedApplicationHealth.ApplicationName、deployedApplicationHealth.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedApplicationHealth.NodeName) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-586">Console.WriteLine("  Application {0}: {1}", deployedApplicationHealth.ApplicationName, deployedApplicationHealth.AggregatedHealthState); Console.WriteLine("    Node Name: " + deployedApplicationHealth.NodeName);</span></span>
                    
                    <span data-ttu-id="4c57b-587">展開済みアプリケーションのヘルス状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-587">// List the deployed application health states.</span></span>
                    <span data-ttu-id="4c57b-588">Console.WriteLine ("配置済みのアプリケーション:") です。IList&lt;DeployedServicePackageHealthState&gt; deployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; foreach (DeployedServicePackageHealthState deployedSPHealthState でdeployedSPHealthStateList) {Console.WriteLine ("アプリケーション:"+ deployedSPHealthState.ApplicationName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedSPHealthState.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedSPHealthState.NodeName) です。Console.WriteLine ("サービス マニフェスト名:"+ deployedSPHealthState.ServiceManifestName);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-588">Console.WriteLine("    Deployed applications:"); IList&lt;DeployedServicePackageHealthState&gt; deployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; foreach (DeployedServicePackageHealthState deployedSPHealthState in deployedSPHealthStateList) { Console.WriteLine("      Application: " + deployedSPHealthState.ApplicationName); Console.WriteLine("        Aggregated Health State: " + deployedSPHealthState.AggregatedHealthState); Console.WriteLine("        Node Name: " + deployedSPHealthState.NodeName); Console.WriteLine("        Service Manifest Name: " + deployedSPHealthState.ServiceManifestName); }</span></span>
                    
            <span data-ttu-id="4c57b-589">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-589">// List the health events.</span></span>
                <span data-ttu-id="4c57b-590">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = deployedApplicationHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-590">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = deployedApplicationHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="4c57b-591">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-591">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="4c57b-592">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-592">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
            <span data-ttu-id="4c57b-593">Console.WriteLine() です。}} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-593">Console.WriteLine(); } } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
            <span data-ttu-id="4c57b-594">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-594">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
            
            <span data-ttu-id="4c57b-595">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-595">return false; }</span></span>
            
            <span data-ttu-id="4c57b-596">true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-596">return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-597"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-597">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-598">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-598">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-599">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-599">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-600">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-600">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-601">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-601">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-602">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-602">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-603"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-603"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-604">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-604">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-605"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-605"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-606"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-606"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-607"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-607"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-608"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-608"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-609"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-609"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-610"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-610"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-611"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-611"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-612"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-612"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-613"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-613"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-614"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-614"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-615"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-615"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-616"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-616"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-617">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-617">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-618"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-618"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-619">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-619">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-620">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-620">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-621">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-621">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-622">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-622">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-623">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-623">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-624">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-624">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-625">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-625">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-626">非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-626">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-627">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4c57b-627">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-628"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-628">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-629">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-629">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-630">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-630">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-631">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-631">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-632">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-632">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-633">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-633">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-634"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-634"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-635">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-635">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-636"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-636"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-637"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-637"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-638"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-638"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-639"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-639"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-640"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-640"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-641"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-641"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-642"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-642"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-643"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-643"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-644"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-644"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-645"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-645"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-646"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-646"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-647"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-647"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-648">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-648">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-649"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-649"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-650">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-650">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-651">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-651">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-652">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-652">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-653">Service Fabric アプリケーションの配置先となるノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-653">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-654">アプリケーションの正常性ポリシーはエンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-654">The application health policy used to evaluate entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-655">指定されたノードで、展開済みの Service Fabric アプリケーションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-655">Asynchronously gets the health of a deployed Service Fabric application on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-656">展開済みの Service Fabric アプリケーションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-656">The health of a deployed Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-657"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-657">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-658">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-658">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-659">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-659">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-660">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-660">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-661">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-661">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-662">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-662">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-663"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-663"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-664">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-664">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-665"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-665"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-666"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-666"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-667"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-667"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-668"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-668"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-669"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-669"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-670"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-670"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-672"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-672"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-674"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-674"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-675"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-675"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-676"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-676"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-677">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-677">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-678"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-678"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-679">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-679">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-680">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-680">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-681">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-681">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-682">Service Fabric アプリケーションの配置先となるノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-682">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-683">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-683">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-684">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-684">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-685">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-685">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-686">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-686">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-687">非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-687">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-688">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4c57b-688">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-689"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-689">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-690">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-690">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-691">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-691">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-692">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-692">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-693">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-693">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-694">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-694">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-695"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-695"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-696">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-696">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-697"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-697"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-698"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-698"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-699"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-699"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-700"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-700"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-701"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-701"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-702"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-702"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-703"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-703"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-704"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-704"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-705"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-705"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-708"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-708"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-709">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-709">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-710"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-710"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-711">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-711">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-712">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-712">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-713">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-713">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-714">Service Fabric アプリケーションの配置先となるノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-714">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-715">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-715">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-716">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-716">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-717">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-717">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-718">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-718">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-719">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-719">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-720">非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-720">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-721">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="4c57b-721">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-722"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-722">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-723">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-723">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-724">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-724">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-725">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-725">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-726">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-726">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-727">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-727">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-728"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-728"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-729">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-729">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-730"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-730"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-731"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-731"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-732"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-732"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-735"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-735"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-736"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-736"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-737"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-737"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-738"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-738"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-739"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-739"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-740"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-740"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-741"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-741"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-742">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-742">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-743"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-743"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-744">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-744">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-745">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-745">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (queryDescription As DeployedServicePackageHealthQueryDescription) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-746">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-746">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-747">非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-747">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-748">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-748">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-749"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-749">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-750">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-750">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-751">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-751">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-752">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-752">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-753">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-753">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-754">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-754">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-755"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-755"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-756">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-756">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-757"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-757"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-758"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-758"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-759"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-759"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-760"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-760"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-761"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-761"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-762"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-762"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-763"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-763"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-764"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-764"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-765"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-765"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-766"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-766"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-767"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-767"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-768"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-768"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-769">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-769">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-770"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-770"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-771">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-771">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-772">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-772">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-773">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-773">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-774">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-774">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-775">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-775">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-776">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-776">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-777">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-777">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-778">非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-778">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-779">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-779">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="4c57b-780">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-780">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="4c57b-781">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-781">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-782">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-782">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-783"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-783"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-784"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-784"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
                <span data-ttu-id="4c57b-785">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-785">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-786">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-786">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-787">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-787">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-788">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-788">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-789">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-789">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-790"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-790"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-791">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-791">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-792">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-792">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-793">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-793">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="4c57b-794">サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-794">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-795">Service Fabric サービスが展開されているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-795">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-796">展開済みの Service Fabric サービス パッケージの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-796">Asynchronously gets the health of a deployed Service Fabric service package.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-797">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-797">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-798">次の例では、展開済みサービス パッケージの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-798">The following example gets the health of a deployed service package.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-799">パブリック静的 bool GetDeployedServicePackageHealth(string clusterConnection) {DeployedApplicationHealth deployedApplicationHealth です。DeployedServicePackageHealth deployedServicePackageHealth です。ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-799">public static bool GetDeployedServicePackageHealth(string clusterConnection) { DeployedApplicationHealth deployedApplicationHealth; DeployedServicePackageHealth deployedServicePackageHealth; ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="4c57b-800">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-800">// Connect to the cluster.</span></span>
                <span data-ttu-id="4c57b-801">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-801">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="4c57b-802">Console.WriteLine ("サービス パッケージのヘルスを展開します。") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-802">Console.WriteLine("Deployed Service Package Health:");</span></span>
            
                <span data-ttu-id="4c57b-803">再試行してください {//アプリケーションが配置されているノードを決定します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-803">try { // Determine the nodes where the application has been deployed.</span></span>
                <span data-ttu-id="4c57b-804">applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-804">applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result;</span></span>
            
                <span data-ttu-id="4c57b-805">各ノードの展開済みサービス パッケージの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-805">// Get the deployed service package health for each node.</span></span>
            <span data-ttu-id="4c57b-806">IList&lt;DeployedApplicationHealthState&gt; deployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedApplicationHealthState でdeployedApplicationHealthStateList) {//サービス マニフェスト名を含む展開されたアプリケーションのヘルスを取得し、/、ノードの名前、サービスの場所が展開されている/。</span><span class="sxs-lookup"><span data-stu-id="4c57b-806">IList&lt;DeployedApplicationHealthState&gt; deployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedApplicationHealthState in deployedApplicationHealthStateList) { // Get the deployed application health, which contains the service manifest name and // the names of the nodes where the service has been deployed.</span></span>
                <span data-ttu-id="4c57b-807">deployedApplicationHealth fabricClient.HealthManager.GetDeployedApplicationHealthAsync (applicationName、deployedApplicationHealthState.NodeName) を = です。結果です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-807">deployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync(applicationName, deployedApplicationHealthState.NodeName).Result;</span></span>
                
                    <span data-ttu-id="4c57b-808">空の場合を返します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-808">// Return if empty.</span></span>
                    <span data-ttu-id="4c57b-809">場合 (deployedApplicationHealth.DeployedServicePackageHealthStates.Count = = 0); false を返します</span><span class="sxs-lookup"><span data-stu-id="4c57b-809">if (deployedApplicationHealth.DeployedServicePackageHealthStates.Count == 0) return false;</span></span>
            
                    <span data-ttu-id="4c57b-810">展開済みサービス パッケージの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-810">// Get the deployed service package health.</span></span>
                    <span data-ttu-id="4c57b-811">deployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync (applicationName、deployedApplicationHealth.DeployedServicePackageHealthStates[0] です。ServiceManifestName、deployedApplicationHealthState.NodeName)。結果です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-811">deployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync(applicationName, deployedApplicationHealth.DeployedServicePackageHealthStates[0].ServiceManifestName, deployedApplicationHealthState.NodeName).Result;</span></span>
                    
                    <span data-ttu-id="4c57b-812">展開済みサービス パッケージの正常性の情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-812">// Display the deployed service package health information.</span></span>
            <span data-ttu-id="4c57b-813">Console.WriteLine ("アプリケーション名:"+ deployedServicePackageHealth.ApplicationName) です。Console.WriteLine ("ノード名:"+ deployedServicePackageHealth.NodeName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedServicePackageHealth.AggregatedHealthState) です。Console.WriteLine ("サービス マニフェスト名:"+ deployedServicePackageHealth.ServiceManifestName) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-813">Console.WriteLine("  Application Name: " + deployedServicePackageHealth.ApplicationName); Console.WriteLine("    Node Name: " + deployedServicePackageHealth.NodeName); Console.WriteLine("    Aggregated Health State: " + deployedServicePackageHealth.AggregatedHealthState); Console.WriteLine("    Service Manifest Name: " + deployedServicePackageHealth.ServiceManifestName);</span></span>
            
            <span data-ttu-id="4c57b-814">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-814">// List the health events.</span></span>
                <span data-ttu-id="4c57b-815">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = deployedServicePackageHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-815">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = deployedServicePackageHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="4c57b-816">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-816">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="4c57b-817">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-817">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="4c57b-818">Console.WriteLine() です。}} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-818">Console.WriteLine(); } } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
            <span data-ttu-id="4c57b-819">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-819">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="4c57b-820">返す場合は false です。} です true を返す。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-820">return false; } return true; }</span></span>
            </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-821"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-821">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-822">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-822">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-823">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-823">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-824">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-824">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-825">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-825">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-826">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-826">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-827"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-827"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-828">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-828">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-829"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-829"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-830"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-830"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-831"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-831"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-832"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-832"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-833"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-833"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-834"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-834"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-835"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-835"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-836"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-836"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-837"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-837"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-838"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-838"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-839"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-839"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-840"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-840"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-841">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-841">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-842"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-842"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-843">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-843">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-844">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-844">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-845">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-845">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="4c57b-846">サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-846">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-847">Service Fabric サービスが展開されているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-847">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-848">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-848">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-849">展開済みの Service Fabric サービス パッケージの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-849">Asynchronously gets the health of a deployed Service Fabric service package.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-850">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-850">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-851"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-851">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-852">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-852">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-853">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-853">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-854">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-854">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-855">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-855">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-856">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-856">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-857"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-857"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-858">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-858">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-859"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-859"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-860"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-860"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-861"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-861"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-862"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-862"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-863"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-863"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-864"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-864"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-865"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-865"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-866"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-866"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-867"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-867"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-868"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-868"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-869"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-869"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-870"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-870"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-871">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-871">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-872"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-872"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-873">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-873">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-874">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-874">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-875">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-875">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="4c57b-876">サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-876">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-877">Service Fabric サービスが展開されているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-877">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-878">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-878">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-879">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-879">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-880">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-880">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-881">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-881">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-882">非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-882">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-883">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-883">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-884"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-884">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-885">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-885">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-886">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-886">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-887">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-887">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-888">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-888">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-889">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-889">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-890"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-890"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-891">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-891">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-892"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-892"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-893"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-893"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-894"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-894"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-895"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-895"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-896"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-896"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-897"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-897"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-898"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-898"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-899"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-899"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-900"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-900"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-901"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-901"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-902"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-902"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-903"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-903"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-904">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-904">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-905"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-905"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-906">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-906">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-907">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-907">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="4c57b-908">Service Fabric アプリケーションの URI。</span><span class="sxs-lookup"><span data-stu-id="4c57b-908">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="4c57b-909">サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-909">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-910">Service Fabric サービスが展開されているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-910">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-911">アプリケーションの正常性ポリシーはエンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-911">The application health policy used to evaluate entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-912">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-912">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-913">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-913">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-914">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-914">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-915">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-915">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-916">非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-916">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-917">展開済みの Service Fabric サービス パッケージの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-917">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-918"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-918">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-919">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-919">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-920">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-920">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-921">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-921">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-922">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-922">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-923">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-923">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-924"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-924"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-925">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-925">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-926"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-926"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-927"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-927"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-928"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-928"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-929"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-929"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-930"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-930"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-931"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-931"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-932"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-932"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-933"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-933"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-934"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-934"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-935"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-935"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-936"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-936"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-937"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-937"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-938">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-938">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-939"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-939"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-940">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-940">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-941">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-941">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (queryDescription As NodeHealthQueryDescription) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-942">正常性ポリシーのようにパラメーターを定義するクエリの説明がなどにフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-942">The query description that defines parameters like health policy, filters etc.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-943">非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-943">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-944">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-944">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-945"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-945">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-946">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-946">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-947">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-947">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-948">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-948">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-949">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-949">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-950">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-950">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-951"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-951"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-952">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-952">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-953"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-953"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-954"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-954"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-955"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-955"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-956"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-956"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-957"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-957"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-958"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-958"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-959"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-959"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-960"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-960"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-961"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-961"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-962"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-962"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-963"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-963"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-964">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-964">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-965"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-965"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-966">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-966">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-967">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-967">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-968">Service Fabric ノード名です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-968">The Service Fabric node name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-969">Service Fabric ノードの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-969">Asynchronously gets the health of a Service Fabric node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-970">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-970">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-971">次の例では、ノードの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-971">The following example gets the health of a node.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-972">パブリック静的 bool GetNodeHealth(string clusterConnection) {NodeHealth nodeHealth です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-972">public static bool GetNodeHealth(string clusterConnection) { NodeHealth nodeHealth;</span></span>
            
                <span data-ttu-id="4c57b-973">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-973">// Connect to the cluster.</span></span>
            <span data-ttu-id="4c57b-974">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-974">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="4c57b-975">ノードの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-975">// Get the node health.</span></span>
            <span data-ttu-id="4c57b-976">再試行してください {nodeHealth fabricClient.HealthManager.GetNodeHealthAsync("Node1") を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-976">try { nodeHealth = fabricClient.HealthManager.GetNodeHealthAsync("Node1").Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="4c57b-977">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-977">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="4c57b-978">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-978">return false; }</span></span>
                
                <span data-ttu-id="4c57b-979">ノードの正常性の情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-979">// Display the node health information.</span></span>
                <span data-ttu-id="4c57b-980">Console.WriteLine ("ノードの正常性:") です。Console.WriteLine ("ノード {0}: {1}"、nodeHealth.NodeName、nodeHealth.AggregatedHealthState) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-980">Console.WriteLine("Node Health:"); Console.WriteLine("  Node {0}: {1}", nodeHealth.NodeName, nodeHealth.AggregatedHealthState);</span></span>
                    
            <span data-ttu-id="4c57b-981">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-981">// List the health events.</span></span>
                    <span data-ttu-id="4c57b-982">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = nodeHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-982">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = nodeHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="4c57b-983">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-983">// List the unhealthy evaluations.</span></span>
                    <span data-ttu-id="4c57b-984">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = nodeHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-984">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = nodeHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="4c57b-985">Console.WriteLine() です。true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-985">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-986"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-986">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-987">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-987">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-988">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-988">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-989">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-989">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-990">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-990">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-991">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-991">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-992"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-992"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-993">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-993">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-994"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-994"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-995"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-995"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-996"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-996"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-997"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-997"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-998"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-998"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-999"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-999"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1000"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1000"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1001"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1001"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1002"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1002"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1003"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1003"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1004"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1004"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1005">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1005">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1006"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1006"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1007">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1007">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1008">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1008">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String, healthPolicy As ClusterHealthPolicy) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-1009">Service Fabric ノード名です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1009">The Service Fabric node name.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1010">クラスターの正常性ポリシーはノードの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1010">The cluster health policy used to evaluate the node health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1011">Service Fabric ノードの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1011">Asynchronously gets the health of a Service Fabric node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1012">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1012">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1013"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1013">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1014">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1014">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1015">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1015">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1016">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1016">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1017">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1017">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1018">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1018">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1019"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1019"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1020">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1020">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1021"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1021"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1022"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1022"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1023"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1023"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1024"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1024"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1025"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1025"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1026"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1026"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1027"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1027"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1028"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1028"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1029"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1029"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1030"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1030"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1031"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1031"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1032">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1032">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1033"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1033"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1034">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1034">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1035">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1035">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1036">正常性ポリシーのようにパラメーターを定義するクエリの説明がなどにフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1036">The query description that defines parameters like health policy, filters etc.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1037">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1037">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1038">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1038">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1039">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1039">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-1040">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1040">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1041">非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1041">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1042">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1042">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1043"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1043">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1044">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1044">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1045">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1045">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1046">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1046">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1047">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1047">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1048">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1048">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1049"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1049"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1050">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1050">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1051"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1051"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1052"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1052"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1053"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1053"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1054"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1054"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1055"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1055"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1056"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1056"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1057"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1057"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1058"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1058"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1059"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1059"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1060"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1060"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1061"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1061"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1062">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1062">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1063"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1063"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1064">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1064">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1065">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1065">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-1066">Service Fabric ノードです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1066">The Service Fabric node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1067">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1067">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1068">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1068">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1069">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1069">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-1070">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1070">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1071">非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1071">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1072">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1072">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1073"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1073">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1074">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1074">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1075">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1075">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1076">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1076">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1077">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1077">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1078">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1078">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1079"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1079"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1080">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1080">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1081"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1081"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1082"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1082"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1083"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1083"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1084"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1084"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1085"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1085"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1086"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1086"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1087"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1087"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1088"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1088"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1089"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1089"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1090"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1090"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1091"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1091"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1092">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1092">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1093"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1093"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1094">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1094">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1095">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1095">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="4c57b-1096">Service Fabric ノードです。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1096">The Service Fabric node.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1097">クラスターの正常性ポリシーはノードの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1097">The cluster health policy used to evaluate the node health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1098">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1098">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1099">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1099">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1100">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1100">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4c57b-1101">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1101">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1102">非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1102">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1103">Service Fabric ノードの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1103">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1104"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1104">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1105">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1105">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1106">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1106">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1107">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1107">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1108">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1108">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1109">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1109">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1110"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1110"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1111">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1111">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1112"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1112"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1113"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1113"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1114"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1114"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1115"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1115"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1116"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1116"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1119"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1119"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1121"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1121"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1122"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1122"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1123">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1123">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1124"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1124"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1125">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1125">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1126">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1126">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (queryDescription As PartitionHealthQueryDescription) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1127">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1127">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1128">非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1128">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1129">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1129">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1130"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1130">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1131">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1131">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1132">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1132">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1133">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1133">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1134">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1134">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1135">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1135">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1136"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1136"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1137">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1137">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1138"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1138"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1139"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1139"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1140"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1140"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1141"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1141"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1142"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1142"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1143"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1143"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1144"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1144"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1145"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1145"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1146"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1146"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1147"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1147"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1148"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1148"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1149">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1149">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1150"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1150"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1151">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1151">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1152">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1152">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1153">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1153">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1154">Service Fabric パーティションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1154">Asynchronously gets the health of a Service Fabric partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1155">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1155">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-1156">次の例では、パーティションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1156">The following example gets the health of a partition.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-1157">パブリック静的 bool GetPartitionHealth(string clusterConnection) {PartitionHealth partitionHealth です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1157">public static bool GetPartitionHealth(string clusterConnection) { PartitionHealth partitionHealth;</span></span>
            
                <span data-ttu-id="4c57b-1158">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1158">// Connect to the cluster.</span></span>
            <span data-ttu-id="4c57b-1159">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1159">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="4c57b-1160">パーティションの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1160">// Get the partition health.</span></span>
            <span data-ttu-id="4c57b-1161">再試行してください {partitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync (新しい Guid("a7206315-e53b-4d05-b59c-e210caa28893")) です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1161">try { partitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync(new Guid("a7206315-e53b-4d05-b59c-e210caa28893")).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="4c57b-1162">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1162">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="4c57b-1163">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1163">return false; }</span></span>
                
                <span data-ttu-id="4c57b-1164">パーティションの正常性の情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1164">// Display the partition health information.</span></span>
                <span data-ttu-id="4c57b-1165">Console.WriteLine ("正常性をパーティション分割:") です。Console.WriteLine ("パーティション ID:"+ partitionHealth.PartitionId) です。Console.WriteLine ("ヘルス状態を集計します。"+ partitionHealth.AggregatedHealthState) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1165">Console.WriteLine("Partition Health:"); Console.WriteLine("  Partition ID: " + partitionHealth.PartitionId); Console.WriteLine("    Aggregated Health State: " + partitionHealth.AggregatedHealthState);</span></span>
                    
            <span data-ttu-id="4c57b-1166">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1166">// List the health events.</span></span>
                    <span data-ttu-id="4c57b-1167">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = partitionHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1167">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = partitionHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                        
            <span data-ttu-id="4c57b-1168">レプリカの正常性状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1168">// List the replica health states.</span></span>
                    <span data-ttu-id="4c57b-1169">Console.WriteLine ("レプリカの正常性状態:") です。IList&lt;ReplicaHealthState&gt; replicaHealthStates = partitionHealth.ReplicaHealthStates; foreach (replicaHealthStates で ReplicaHealthState replicaHealthState) {Console.WriteLine ("ID:"+ replicaHealthState.Id) です。Console.WriteLine ("種類:"+ replicaHealthState.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ replicaHealthState.AggregatedHealthState) です。Console.WriteLine ("パーティション ID:"+ replicaHealthState.PartitionId);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1169">Console.WriteLine("    Replica Health States:"); IList&lt;ReplicaHealthState&gt; replicaHealthStates = partitionHealth.ReplicaHealthStates; foreach (ReplicaHealthState replicaHealthState in replicaHealthStates) { Console.WriteLine("      ID: " + replicaHealthState.Id); Console.WriteLine("        Kind: " + replicaHealthState.Kind); Console.WriteLine("        Aggregated Health State: " + replicaHealthState.AggregatedHealthState); Console.WriteLine("        Partition ID: " + replicaHealthState.PartitionId); }</span></span>
                
            <span data-ttu-id="4c57b-1170">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1170">// List the unhealthy evaluations.</span></span>
                <span data-ttu-id="4c57b-1171">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = partitionHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1171">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = partitionHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
                <span data-ttu-id="4c57b-1172">Console.WriteLine() です。true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1172">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1173"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1173">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1174">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1174">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1175">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1175">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1176">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1176">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1177">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1177">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1178">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1178">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1179"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1179"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1180">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1180">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1181"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1181"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1182"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1182"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1183"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1183"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1184"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1184"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1185"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1185"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1186"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1186"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1188"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1188"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1190"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1190"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1191"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1191"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1192">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1192">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1193"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1193"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1194">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1194">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1195">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1195">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid, healthPolicy As ApplicationHealthPolicy) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1196">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1196">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1197">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1197">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1198">Service Fabric パーティションの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1198">Asynchronously gets the health of a Service Fabric partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1199">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1199">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1200"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1200">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1201">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1201">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1202">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1202">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1203">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1203">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1204">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1204">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1205">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1205">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1206"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1206"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1207">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1207">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1208"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1208"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1209"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1209"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1210"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1210"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1211"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1211"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1212"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1212"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1213"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1213"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1214"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1214"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1215"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1215"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1216"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1216"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1217"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1217"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1218"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1218"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1219">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1219">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1220"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1220"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1221">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1221">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1222">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1222">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1223">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1223">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1224">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1224">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1225">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1225">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1226">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1226">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1227">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1227">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1228">非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1228">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1229">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1229">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1230"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1230">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1231">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1231">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1232">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1232">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1233">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1233">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1234">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1234">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1235">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1235">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1236"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1236"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1237">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1237">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1238"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1238"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1239"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1239"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1240"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1240"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1241"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1241"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1242"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1242"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1243"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1243"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1244"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1244"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1245"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1245"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1246"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1246"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1247"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1247"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1248"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1248"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1249">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1249">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1250"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1250"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1251">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1251">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1252">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1252">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1253">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1253">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1254">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1254">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1255">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1255">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1256">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1256">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1257">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1257">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1258">非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1258">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1259">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1259">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1260"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1260">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1261">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1261">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1262">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1262">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1263">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1263">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1264">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1264">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1265">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1265">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1266"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1266"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1267">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1267">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1268"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1268"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1269"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1269"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1270"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1270"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1271"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1271"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1272"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1272"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1273"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1273"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1274"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1274"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1275"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1275"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1276"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1276"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1277"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1277"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1278"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1278"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1279">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1279">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1280"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1280"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1281">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1281">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1282">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1282">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1283">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1283">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1284">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1284">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1285">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1285">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1286">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1286">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1287">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1287">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1288">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1288">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1289">非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1289">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1290">Service Fabric パーティションの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1290">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1291"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1291">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1292">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1292">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1293">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1293">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1294">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1294">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1295">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1295">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1296">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1296">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1297"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1297"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1298">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1298">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1299"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1299"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1300"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1300"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1301"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1301"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1302"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1302"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1303"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1303"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1304"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1304"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1305"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1305"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1306"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1306"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1307"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1307"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1308"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1308"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1309"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1309"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1310">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1310">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1311"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1311"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1312">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1312">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1313">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1313">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (queryDescription As ReplicaHealthQueryDescription) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1314">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1314">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1315">クエリの説明で指定された Service Fabric レプリカの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1315">Asynchronously gets the health of a Service Fabric replica specified by the query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1316">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1316">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1317"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1317">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1318">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1318">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1319">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1319">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1320">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1320">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1321">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1321">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1322">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1322">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1323"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1323"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1324">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1324">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1325"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1325"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1326"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1326"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1327"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1327"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1328"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1328"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1330"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1330"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1331"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1331"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1332"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1332"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1333"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1333"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1334"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1334"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1335"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1335"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1336">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1336">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1337"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1337"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1338">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1338">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1339">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1339">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1340">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1340">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="4c57b-1341">Service Fabric レプリカの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1341">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1342">Service Fabric レプリカの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1342">Asynchronously gets the health of a Service Fabric replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1343">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1343">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-1344">次の例では、レプリカの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1344">The following example gets the health of a replica.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-1345">パブリック静的 bool GetReplicaHealth(string clusterConnection) {ReplicaHealth replicaHealth です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1345">public static bool GetReplicaHealth(string clusterConnection) { ReplicaHealth replicaHealth;</span></span>
            
                <span data-ttu-id="4c57b-1346">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1346">// Connect to the cluster.</span></span>
            <span data-ttu-id="4c57b-1347">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1347">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="4c57b-1348">レプリカの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1348">// Get the replica health.</span></span>
            <span data-ttu-id="4c57b-1349">再試行してください {replicaHealth fabricClient.HealthManager.GetReplicaHealthAsync (新しい Guid("a7206315-e53b-4d05-b59c-e210caa28893") 130538257146083818 など) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1349">try { replicaHealth = fabricClient.HealthManager.GetReplicaHealthAsync( new Guid("a7206315-e53b-4d05-b59c-e210caa28893"), 130538257146083818).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="4c57b-1350">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1350">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="4c57b-1351">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1351">return false; }</span></span>
            
                <span data-ttu-id="4c57b-1352">Console.WriteLine ("レプリカの正常性:") です。Console.WriteLine ("ID:"+ replicaHealth.Id) です。Console.WriteLine ("ヘルス状態を集計します。"+ replicaHealth.AggregatedHealthState) です。Console.WriteLine ("種類:"+ replicaHealth.Kind) です。Console.WriteLine ("パーティション ID:"+ replicaHealth.PartitionId) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1352">Console.WriteLine("Replica Health:"); Console.WriteLine("  ID: " + replicaHealth.Id); Console.WriteLine("    Aggregated Health State: " + replicaHealth.AggregatedHealthState); Console.WriteLine("    Kind: " + replicaHealth.Kind); Console.WriteLine("    Partition ID: " + replicaHealth.PartitionId);</span></span>
                
                <span data-ttu-id="4c57b-1353">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1353">// List the health events.</span></span>
                    <span data-ttu-id="4c57b-1354">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = replicaHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1354">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = replicaHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
                    <span data-ttu-id="4c57b-1355">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1355">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="4c57b-1356">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = replicaHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1356">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = replicaHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
                    <span data-ttu-id="4c57b-1357">Console.WriteLine() です。true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1357">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1358"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1358">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1359">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1359">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1360">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1360">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1361">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1361">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1362">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1362">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1363">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1363">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1364"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1364"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1365">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1365">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1366"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1366"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1367"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1367"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1368"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1368"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1369"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1369"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1370"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1370"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1371"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1371"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1372"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1372"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1373"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1373"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1374"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1374"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1375"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1375"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1376"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1376"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1377">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1377">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1378"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1378"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1379">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1379">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1380">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1380">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1381">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1381">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1382">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1382">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1383">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1383">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1384">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1384">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1385">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1385">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1386">非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1386">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1387">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1387">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1388"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1388">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1389">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1389">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1390">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1390">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1391">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1391">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1392">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1392">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1393">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1393">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1394"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1394"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1395">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1395">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1396"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1396"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1397"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1397"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1398"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1398"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1399"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1399"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1400"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1400"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1401"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1401"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1402"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1402"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1403"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1403"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1404"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1404"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1405"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1405"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1406"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1406"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1407">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1407">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1408"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1408"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1409">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1409">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1410">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1410">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long, healthPolicy As ApplicationHealthPolicy) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1411">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1411">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="4c57b-1412">Service Fabric レプリカの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1412">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1413">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1413">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1414">Service Fabric レプリカの正常性を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1414">Asynchronously gets the health of a Service Fabric replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1415">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1415">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1416"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1416">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1417">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1417">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1418">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1418">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1419">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1419">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1420">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1420">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1421">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1421">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1422"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1422"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1423">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1423">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1424"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1424"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1425"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1425"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1426"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1426"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1427"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1427"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1428"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1428"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1429"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1429"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1430"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1430"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1431"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1431"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1432"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1432"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1433"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1433"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1434"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1434"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1435">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1435">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1436"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1436"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1437">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1437">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1438">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1438">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1439">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1439">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="4c57b-1440">Service Fabric レプリカの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1440">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1441">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1441">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1442">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1442">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1443">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1443">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1444">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1444">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1445">非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1445">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1446">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1446">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1447"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1447">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1448">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1448">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1449">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1449">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1450">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1450">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1451">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1451">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1452">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1452">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1453"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1453"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1454">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1454">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1455"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1455"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1456"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1456"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1457"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1457"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1458"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1458"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1459"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1459"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1460"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1460"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1461"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1461"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1462"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1462"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1463"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1463"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1464"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1464"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1465"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1465"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1466">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1466">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1467"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1467"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1468">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1468">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1469">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1469">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="4c57b-1470">Service Fabric パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1470">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="4c57b-1471">Service Fabric レプリカの ID。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1471">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1472">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1472">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1473">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1473">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1474">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1474">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1475">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1475">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1476">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1476">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1477">非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1477">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1478">Service Fabric レプリカの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1478">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1479"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1479">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1480">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1480">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1481">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1481">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1482">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1482">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1483">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1483">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1484">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1484">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1485"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1485"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1486">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1486">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1487"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1487"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1488"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1488"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1489"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1489"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1490"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1490"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1491"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1491"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1492"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1492"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1493"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1493"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1494"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1494"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1495"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1495"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1496"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1496"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1497"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1497"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1498">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1498">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1499"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1499"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1500">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1500">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1501">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1501">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (queryDescription As ServiceHealthQueryDescription) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1502">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1502">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1503">非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1503">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1504">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1504">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1505"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1505">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1506">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1506">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1507">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1507">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1508">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1508">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1509">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1509">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1510">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1510">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1511"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1511"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1512">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1512">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1513"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1513"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1514"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1514"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1515"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1515"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1516"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1516"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1517"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1517"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1518"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1518"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1519"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1519"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1520"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1520"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1521"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1521"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1522"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1522"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1523"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1523"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1524"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1524"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1525">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1525">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1526"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1526"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1527">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1527">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1528">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1528">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="4c57b-1529">Service Fabric サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1529">The name of the Service Fabric service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1530">Service Fabric サービスのヘルスを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1530">Asynchronously gets the health of a Service Fabric service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1531">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1531">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="4c57b-1532">次の例では、サービスの正常性を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1532">The following example gets the health of a service.</span></span></para>
          <code language="c#"><span data-ttu-id="4c57b-1533">パブリック静的 bool GetServiceHealth(string clusterConnection) {ServiceHealth serviceHealth です。Uri の serviceName = 新しい Uri("fabric:/myapp/todo/svc1") です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1533">public static bool GetServiceHealth(string clusterConnection) { ServiceHealth serviceHealth; Uri serviceName = new Uri("fabric:/myapp/todo/svc1");</span></span>
            
                <span data-ttu-id="4c57b-1534">クラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1534">// Connect to the cluster.</span></span>
                <span data-ttu-id="4c57b-1535">FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1535">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
            
                <span data-ttu-id="4c57b-1536">サービスのヘルス状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1536">// Get the service health.</span></span>
                <span data-ttu-id="4c57b-1537">再試行してください {serviceHealth fabricClient.HealthManager.GetServiceHealthAsync(serviceName) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1537">try { serviceHealth = fabricClient.HealthManager.GetServiceHealthAsync(serviceName).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
                <span data-ttu-id="4c57b-1538">場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1538">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="4c57b-1539">返す場合は false です。}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1539">return false; }</span></span>
                    
                <span data-ttu-id="4c57b-1540">Console.WriteLine ("サービスのヘルス:") です。Console.WriteLine ("サービス {0}: {1}"、serviceHealth.ServiceName、serviceHealth.AggregatedHealthState) です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1540">Console.WriteLine("Service Health:"); Console.WriteLine("  Service {0}: {1}", serviceHealth.ServiceName, serviceHealth.AggregatedHealthState);</span></span>
                
                <span data-ttu-id="4c57b-1541">正常性の状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1541">// List the health states.</span></span>
                    <span data-ttu-id="4c57b-1542">Console.WriteLine ("パーティションの正常性状態:") です。IList&lt;PartitionHealthState&gt; partitionHealthStates = serviceHealth.PartitionHealthStates; foreach (partitionHealthStates で PartitionHealthState partitionHealthState) {Console.WriteLine ("集計された正常性状態。"+ partitionHealthState.AggregatedHealthState) です。Console.WriteLine ("パーティション ID:"+ partitionHealthState.PartitionId);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1542">Console.WriteLine("    Partition Health States:"); IList&lt;PartitionHealthState&gt; partitionHealthStates = serviceHealth.PartitionHealthStates; foreach (PartitionHealthState partitionHealthState in partitionHealthStates) { Console.WriteLine("      Aggregated Health State: " + partitionHealthState.AggregatedHealthState); Console.WriteLine("      Partition ID: " + partitionHealthState.PartitionId); }</span></span>
            
                    <span data-ttu-id="4c57b-1543">正常性イベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1543">// List the health events.</span></span>
            <span data-ttu-id="4c57b-1544">Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = serviceHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1544">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = serviceHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
                    <span data-ttu-id="4c57b-1545">異常な評価を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1545">// List the unhealthy evaluations.</span></span>
                <span data-ttu-id="4c57b-1546">Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = serviceHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1546">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = serviceHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
                <span data-ttu-id="4c57b-1547">Console.WriteLine() です。true を返す}</span><span class="sxs-lookup"><span data-stu-id="4c57b-1547">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1548"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1548">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1549">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1549">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1550">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1550">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1551">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1551">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1552">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1552">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1553">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1553">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1555">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1555">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1568">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1568">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1570">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1570">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1571">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1571">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="4c57b-1572">Service Fabric サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1572">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1573">アプリケーションの正常性ポリシーはサービスのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1573">The application health policy used to evaluate service health.</span></span></param>
        <summary>
          <para><span data-ttu-id="4c57b-1574">Service Fabric サービスのヘルスを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1574">Asynchronously gets the health of a Service Fabric service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1575">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1575">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1576"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1576">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1577">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1577">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1578">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1578">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1579">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1579">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1580">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1580">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1581">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1581">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1582"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1582"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1583">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1583">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1584"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1584"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1585"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1585"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1586"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1586"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1587"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1587"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1588"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1588"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1589"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1589"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1590"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1590"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1591"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1591"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1592"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1592"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1593"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1593"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1594"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1594"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1595"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1595"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1596">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1596">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1597"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1597"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1598">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1598">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1599">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1599">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><span data-ttu-id="4c57b-1600">クエリの説明。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1600">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1601">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1601">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1602">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1602">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1603">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1603">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1604">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1604">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1605">非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1605">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1606">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1606">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1607"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1607">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1608">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1608">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1609">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1609">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1610">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1610">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1611">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1611">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1612">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1612">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1613"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1613"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1614">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1614">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1615"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1615"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1616"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1616"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1617"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1617"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1618"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1618"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1619"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1619"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1620"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1620"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1621"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1621"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1622"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1622"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1623"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1623"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1624"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1624"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1625"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1625"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1626"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1626"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1627">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1627">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1628"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1628"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1629">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1629">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1630">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1630">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="4c57b-1631">Service Fabric サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1631">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1632">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1632">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1633">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1633">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1634">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1634">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1635">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1635">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1636">非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1636">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1637">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1637">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1638"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1638">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1639">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1639">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1640">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1640">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1641">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1641">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1642">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1642">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1643">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1643">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1644"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1644"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1645">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1645">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1646"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1646"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1647"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1647"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1648"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1648"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1649"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1649"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1650"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1650"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1651"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1651"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1652"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1652"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1653"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1653"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1654"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1654"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1655"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1655"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1656"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1656"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1657"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1657"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1658">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1658">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1659"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1659"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1660">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1660">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1661">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1661">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="4c57b-1662">Service Fabric サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1662">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="4c57b-1663">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1663">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="4c57b-1664">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1664">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4c57b-1665">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1665">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="4c57b-1666">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1666">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="4c57b-1667">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1667">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1668">非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1668">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4c57b-1669">Service Fabric サービスの正常性。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1669">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1670"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1670">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1671">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1671">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1672">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1672">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="4c57b-1673">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1673">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1674">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1674">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="4c57b-1675">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1675">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1676"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1676"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1677">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1677">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1678"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1678"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1679"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1679"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1680"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1680"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1681"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1681"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1682"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1682"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1683"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1683"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1684"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1684"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1685"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1685"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1686"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1686"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1687"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1687"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1688"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1688"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1689"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1689"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="4c57b-1690">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1690">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1691"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1691"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1692">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1692">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1693">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1693">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport -&gt; unit" Usage="healthClient.ReportHealth healthReport" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para><span data-ttu-id="4c57b-1694">送信するための <see cref="T:System.Fabric.Health.HealthReport" />。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1694">The <see cref="T:System.Fabric.Health.HealthReport" /> to submit.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1695">Service Fabric エンティティのヘルスをレポートします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1695">Reports health on a Service Fabric entity.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="4c57b-1696">クラスターを保護すると、正常性のクライアント管理者のアクセス許可をレポートを送信できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1696">When a cluster is secured, the health client needs administrator permission to be able to send the reports.</span></span>
             <span data-ttu-id="4c57b-1697">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">FabricClient Api を使用してクラスターに接続する</see>です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1697">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">connecting to a cluster using the FabricClient APIs</see>.</span></span>
            </para>
          <para>
             <span data-ttu-id="4c57b-1698">正常性レポートの詳細については、次を参照してください。 <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric の正常性の監視</see>です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1698">For more information about health reporting, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric health monitoring</see>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1699"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1699">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1700">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1700">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1701">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1701">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1702">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1702">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1703"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1703"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1704"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1704"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1705"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1705"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1707"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1707"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1708"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1708"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1709"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1709"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1710"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1710"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1711"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1711"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1712"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1712"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1713"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1713"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1714">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1714">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1715">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1715">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="healthClient.ReportHealth (healthReport, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para><span data-ttu-id="4c57b-1716">送信するための <see cref="T:System.Fabric.Health.HealthReport" />。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1716">The <see cref="T:System.Fabric.Health.HealthReport" /> to submit.</span></span></para>
        </param>
        <param name="sendOptions">
          <para><span data-ttu-id="4c57b-1717"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1717">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4c57b-1718">Service Fabric エンティティおよびパス上のレポートの正常性は、レポートを送信する方法を制御するオプションを送信します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1718">Reports health on a Service Fabric entity and passes send options to control how the report is sent.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="4c57b-1719">クラスターを保護すると、正常性のクライアント管理者のアクセス許可をレポートを送信できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1719">When a cluster is secured, the health client needs administrator permission to be able to send the reports.</span></span>
             <span data-ttu-id="4c57b-1720">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">FabricClient Api を使用してクラスターに接続します。</see></span><span class="sxs-lookup"><span data-stu-id="4c57b-1720">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">connecting to a cluster using the FabricClient APIs.</see></span></span></para>
          <para>
             <span data-ttu-id="4c57b-1721">正常性レポートの詳細については、次を参照してください。 <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric の正常性の監視</see>です。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1721">For more information about health reporting, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric health monitoring</see>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="4c57b-1722"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1722">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="4c57b-1723">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1723">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="4c57b-1724">メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1724">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="4c57b-1725">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1725">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1726"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1726"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1727"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1727"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1728"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1728"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1729"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1729"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1730"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1730"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1731"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1731"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1732"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1732"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1733"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1733"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1735"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1735"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="4c57b-1736"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></span><span class="sxs-lookup"><span data-stu-id="4c57b-1736"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="4c57b-1737">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1737">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="4c57b-1738">この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</span><span class="sxs-lookup"><span data-stu-id="4c57b-1738">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>