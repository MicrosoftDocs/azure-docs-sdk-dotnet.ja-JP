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
            Service Fabric サービスのサービス パッケージのライセンス認証モードをについて説明します。 これが、サービスの作成時に指定されて (を使用して<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) または ServiceGroup (を使用して<see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) を介して<see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />です。
            </para>
      <para>
            サービスまたは ServiceGroup、作成中に値が指定されていないかどうかは、既定値は<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />モード。
            </para>
    </summary>
    <remarks>
      <para>
            ここで、ApplicationType 'AppTypeA' を含む ServicePackage 'ServicePackageA' 'ServiceTypeA' を登録する必要があるし、'ServiceTypeA' の多くのサービスを作成する例を検討してください。 言う 'ファブリック: App1_of_AppTypeA/Serv_1' を 'ファブリック: App1_of_AppTypeA/Serv_N' ServicePackageActivation モードと<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />と 'ファブリック: App1_of_AppTypeA/Serv_11' を 'ファブリック: App1_of_AppTypeA/Serv_NN' ServicePackageActivation モードと<see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.
            </para>
      <para>
            指定したノード、レプリカ (またはのインスタンス) サービスの 'ファブリック: App1_of_AppTypeA/Serv_1' に 'ファブリック: App1_of_AppTypeA/Serv_N' が配置される 'ServicePackageA' のライセンス認証の同じ内部の<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />空の文字列は常になります。 ただし、レプリカ (インスタンス) のそれぞれの 'ファブリック: App1_of_AppTypeA/Serv_11' を 'ファブリック: App1_of_AppTypeA/Serv_NN' は、'ServicePackageA' の専用独自アクティブ化し、これらの各でアクティブ化がとして一意の空でない文字列<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.
            </para>
      <para>
            サービスを作成した後は、取得<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />のクエリを実行してノード上のアクティブ化された ServicePackage(s)<see cref="T:System.Fabric.Query.DeployedServicePackageList" />を使用してそのノードで<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />です。
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
            ライセンス認証ではこのモード、各レプリカまたは特定のノードで、サービスのインスタンスは、ノードのサービス パッケージの独自の専用のライセンス認証があります。
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
            これは、既定のライセンス認証モードです。 このライセンス認証モード、レプリカ、または特定のノードで、サービスのさまざまなパーティションからのインスタンスを共有ノードでのサービス パッケージを同じライセンス認証します。
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>