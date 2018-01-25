<Type Name="IStatelessServiceFactory" FullName="System.Fabric.IStatelessServiceFactory">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceFactory" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceFactory" />
  <TypeSignature Language="F#" Value="type IStatelessServiceFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="894a8-101">ステートレス サービスの特定の型のインスタンスの作成を担当するステートレス サービス ファクトリを表します。</span><span class="sxs-lookup"><span data-stu-id="894a8-101">Represents a stateless service factory that is responsible for creating instances of a specific type of stateless service.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="894a8-102">ステートレス サービス ファクトリが登録されている、<see cref="T:System.Fabric.FabricRuntime" />を介してサービス ホストによって<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="894a8-102">Stateless service factories are registered with the <see cref="T:System.Fabric.FabricRuntime" /> by service hosts via <see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" /> or <see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public System.Fabric.IStatelessServiceInstance CreateInstance (string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IStatelessServiceInstance CreateInstance(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceFactory.CreateInstance(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance (serviceTypeName As String, serviceName As Uri, initializationData As Byte(), partitionId As Guid, instanceId As Long) As IStatelessServiceInstance" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.IStatelessServiceInstance" Usage="iStatelessServiceFactory.CreateInstance (serviceTypeName, serviceName, initializationData, partitionId, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServiceInstance</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="instanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="894a8-103">Service Fabric は、作成するように要求するサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="894a8-103">The service type that Service Fabric requests to be created.</span></span></para>
        </param>
        <param name="serviceName">
          <para><span data-ttu-id="894a8-104"><c>ファブリック:/名</c>(Uri) のこのレプリカが関連付けられているサービスです。</span><span class="sxs-lookup"><span data-stu-id="894a8-104">The <c>fabric:/ name</c> (Uri) of the service with which this replica is associated.</span></span> </para>
        </param>
        <param name="initializationData">
          <para><span data-ttu-id="894a8-105">このサービスの一部として渡された最初の初期化データを格納するバイト配列<see cref="T:System.Fabric.Description.ServiceDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="894a8-105">A byte array that contains the initialization data which was originally passed as a part of this service’s <see cref="T:System.Fabric.Description.ServiceDescription" />.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="894a8-106">パーティション ID (GUID) このレプリカが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="894a8-106">The partition ID (GUID) with which this replica is associated.</span></span> </para>
        </param>
        <param name="instanceId">
          <para><span data-ttu-id="894a8-107">型のこのレプリカに対してレプリカ ID<see cref="T:System.Int64" />です。</span><span class="sxs-lookup"><span data-stu-id="894a8-107">The replica ID for this replica of type <see cref="T:System.Int64" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="894a8-108">特定のサービスのステートレス サービス インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="894a8-108">Creates a stateless service instance for a particular service.</span></span> <span data-ttu-id="894a8-109">このメソッドは、Service Fabric によって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="894a8-109">This method is called by Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="894a8-110"><see cref="T:System.Fabric.IStatelessServiceInstance" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="894a8-110">Returns <see cref="T:System.Fabric.IStatelessServiceInstance" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>