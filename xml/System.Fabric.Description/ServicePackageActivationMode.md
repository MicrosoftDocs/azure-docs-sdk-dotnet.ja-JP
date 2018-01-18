<Type Name="ServicePackageActivationMode" FullName="System.Fabric.Description.ServicePackageActivationMode">
  <TypeSignature Language="C#" Value="public enum ServicePackageActivationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePackageActivationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePackageActivationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePackageActivationMode" />
  <TypeSignature Language="F#" Value="type ServicePackageActivationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Service Fabric サービスのサービス パッケージのライセンス認証モードをについて説明します。 <span data-ttu-id="59ba3-102">これが、サービスの作成時に指定されて (を使用して<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) または ServiceGroup (を使用して<see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) を介して<see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="59ba3-102">This is specified at the time of creating the Service (using <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) or ServiceGroup (using <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) via <see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="59ba3-103">サービスまたは ServiceGroup、作成中に値が指定されていないかどうかは、既定値は<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />モード。</span><span class="sxs-lookup"><span data-stu-id="59ba3-103">If no value is specified while creating the Service or ServiceGroup, then it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> mode.</span></span>
            </para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="59ba3-104">ここで、ApplicationType 'AppTypeA' を含む ServicePackage 'ServicePackageA' 'ServiceTypeA' を登録する必要があるし、'ServiceTypeA' の多くのサービスを作成する例を検討してください。</span><span class="sxs-lookup"><span data-stu-id="59ba3-104">Consider an example where you have an ApplicationType 'AppTypeA' which contains ServicePackage 'ServicePackageA' which registers 'ServiceTypeA' and you create many Service(s) of 'ServiceTypeA'.</span></span> <span data-ttu-id="59ba3-105">言う 'ファブリック: App1_of_AppTypeA/Serv_1' を 'ファブリック: App1_of_AppTypeA/Serv_N' ServicePackageActivation モードと<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />と 'ファブリック: App1_of_AppTypeA/Serv_11' を 'ファブリック: App1_of_AppTypeA/Serv_NN' ServicePackageActivation モードと<see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.</span><span class="sxs-lookup"><span data-stu-id="59ba3-105">Say 'fabric:/App1_of_AppTypeA/Serv_1' to 'fabric:/App1_of_AppTypeA/Serv_N' with ServicePackageActivation mode <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> and 'fabric:/App1_of_AppTypeA/Serv_11' to 'fabric:/App1_of_AppTypeA/Serv_NN' with ServicePackageActivation mode <see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="59ba3-106">指定したノード、レプリカ (またはのインスタンス) サービスの 'ファブリック: App1_of_AppTypeA/Serv_1' に 'ファブリック: App1_of_AppTypeA/Serv_N' が配置される 'ServicePackageA' のライセンス認証の同じ内部の<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />空の文字列は常になります。</span><span class="sxs-lookup"><span data-stu-id="59ba3-106">On a given node, replica (or instance) of service 'fabric:/App1_of_AppTypeA/Serv_1' to 'fabric:/App1_of_AppTypeA/Serv_N' will be placed inside the same activation of 'ServicePackageA' whose <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> will always be an empty string.</span></span> <span data-ttu-id="59ba3-107">ただし、レプリカ (インスタンス) のそれぞれの 'ファブリック: App1_of_AppTypeA/Serv_11' を 'ファブリック: App1_of_AppTypeA/Serv_NN' は、'ServicePackageA' の専用独自アクティブ化し、これらの各でアクティブ化がとして一意の空でない文字列<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.</span><span class="sxs-lookup"><span data-stu-id="59ba3-107">However, replica (or instance) of each of  'fabric:/App1_of_AppTypeA/Serv_11' to 'fabric:/App1_of_AppTypeA/Serv_NN' will be placed in its own dedicated activation of 'ServicePackageA' and each of these activation will have a unique non-empty string as <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="59ba3-108">サービスを作成した後は、取得<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />のクエリを実行してノード上のアクティブ化された ServicePackage(s)<see cref="T:System.Fabric.Query.DeployedServicePackageList" />を使用してそのノードで<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />です。</span><span class="sxs-lookup"><span data-stu-id="59ba3-108">After you have created your service, you can obtain <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of activated ServicePackage(s) on a node by querying <see cref="T:System.Fabric.Query.DeployedServicePackageList" /> on that node using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ExclusiveProcess">
      <MemberSignature Language="C#" Value="ExclusiveProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode ExclusiveProcess = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberSignature Language="VB.NET" Value="ExclusiveProcess" />
      <MemberSignature Language="F#" Value="ExclusiveProcess = 1" Usage="System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="59ba3-109">ライセンス認証ではこのモード、各レプリカまたは特定のノードで、サービスのインスタンスは、ノードのサービス パッケージの独自の専用のライセンス認証があります。</span><span class="sxs-lookup"><span data-stu-id="59ba3-109">With this activation mode, each replica or instance of service, on a given node, will have its own dedicated activation of service package on a node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="SharedProcess">
      <MemberSignature Language="C#" Value="SharedProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode SharedProcess = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberSignature Language="VB.NET" Value="SharedProcess" />
      <MemberSignature Language="F#" Value="SharedProcess = 0" Usage="System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="59ba3-110">これは、既定のライセンス認証モードです。</span><span class="sxs-lookup"><span data-stu-id="59ba3-110">This is the default activation mode.</span></span> <span data-ttu-id="59ba3-111">このライセンス認証モード、レプリカ、または特定のノードで、サービスのさまざまなパーティションからのインスタンスを共有ノードでのサービス パッケージを同じライセンス認証します。</span><span class="sxs-lookup"><span data-stu-id="59ba3-111">With this activation mode, replica(s) or instance(s) from different partition(s) of service, on a given node, will share same activation of service package on a node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>