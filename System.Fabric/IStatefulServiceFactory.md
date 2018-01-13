<Type Name="IStatefulServiceFactory" FullName="System.Fabric.IStatefulServiceFactory">
  <TypeSignature Language="C#" Value="public interface IStatefulServiceFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServiceFactory" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServiceFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServiceFactory" />
  <TypeSignature Language="F#" Value="type IStatefulServiceFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="8a157-101">ステートフル サービスの特定の種類のレプリカの作成を担当するステートフルなサービス ファクトリを表します。</span><span class="sxs-lookup"><span data-stu-id="8a157-101">Represents a stateful service factory that is responsible for creating replicas of a specific type of stateful service.</span></span> <span data-ttu-id="8a157-102">ステートフルなサービス ファクトリに登録されている、<see cref="T:System.Fabric.FabricRuntime" />を介してサービス ホストによって<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="8a157-102">Stateful service factories are registered with the <see cref="T:System.Fabric.FabricRuntime" /> by service hosts via <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" /> or <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.IStatefulServiceReplica CreateReplica (string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IStatefulServiceReplica CreateReplica(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceFactory.CreateReplica(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateReplica (serviceTypeName As String, serviceName As Uri, initializationData As Byte(), partitionId As Guid, replicaId As Long) As IStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="abstract member CreateReplica : string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.IStatefulServiceReplica" Usage="iStatefulServiceFactory.CreateReplica (serviceTypeName, serviceName, initializationData, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="8a157-103">Service Fabric は、作成するように要求するサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="8a157-103">The service type that Service Fabric requests to be created.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="8a157-104">ファブリック: (Uri) をこのレプリカが関連付けられているサービスの名前/です。</span><span class="sxs-lookup"><span data-stu-id="8a157-104">The fabric:/ name (Uri) of the service with which this replica is associated.</span></span></para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="8a157-105">このサービスの一部として渡された最初の初期化データを格納するバイト配列<see cref="T:System.Fabric.Description.ServiceDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="8a157-105">A byte array that contains the initialization data which was originally passed as a part of this service’s <see cref="T:System.Fabric.Description.ServiceDescription" />.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="8a157-106">このレプリカが関連付けられている GUID の種類のパーティション ID です。</span><span class="sxs-lookup"><span data-stu-id="8a157-106">The partition ID of type, a GUID, with which this replica is associated.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="8a157-107">レプリカ ID 型のこのレプリカの長さ。</span><span class="sxs-lookup"><span data-stu-id="8a157-107">The replica ID of type long for this replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="8a157-108">特定のサービスのステートフル サービス レプリカの作成に Service Fabric によって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="8a157-108">Called by Service Fabric to create a stateful service replica for a particular service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8a157-109"><see cref="T:System.Fabric.IStatefulServiceReplica" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="8a157-109">Returns <see cref="T:System.Fabric.IStatefulServiceReplica" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>