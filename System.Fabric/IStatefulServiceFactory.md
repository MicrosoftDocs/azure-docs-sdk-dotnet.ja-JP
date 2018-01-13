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
      <para>ステートフル サービスの特定の種類のレプリカの作成を担当するステートフルなサービス ファクトリを表します。 ステートフルなサービス ファクトリに登録されている、<see cref="T:System.Fabric.FabricRuntime" />を介してサービス ホストによって<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
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
          <para>Service Fabric は、作成するように要求するサービスの種類。</para>
        </param>
        <param name="serviceName">
          <para>ファブリック: (Uri) をこのレプリカが関連付けられているサービスの名前/です。</para>
        </param>
        <param name="initializationData">
          <para>このサービスの一部として渡された最初の初期化データを格納するバイト配列<see cref="T:System.Fabric.Description.ServiceDescription" />です。</para>
        </param>
        <param name="partitionId">
          <para>このレプリカが関連付けられている GUID の種類のパーティション ID です。</para>
        </param>
        <param name="replicaId">
          <para>レプリカ ID 型のこのレプリカの長さ。 </para>
        </param>
        <summary>
          <para>特定のサービスのステートフル サービス レプリカの作成に Service Fabric によって呼び出されます。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IStatefulServiceReplica" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>