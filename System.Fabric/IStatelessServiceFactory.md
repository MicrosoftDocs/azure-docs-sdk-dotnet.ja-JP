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
      <para>ステートレス サービスの特定の型のインスタンスの作成を担当するステートレス サービス ファクトリを表します。 </para>
    </summary>
    <remarks>
      <para>ステートレス サービス ファクトリが登録されている、<see cref="T:System.Fabric.FabricRuntime" />を介してサービス ホストによって<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
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
          <para>Service Fabric は、作成するように要求するサービスの種類。</para>
        </param>
        <param name="serviceName">
          <para><c>ファブリック:/名</c>(Uri) のこのレプリカが関連付けられているサービスです。 </para>
        </param>
        <param name="initializationData">
          <para>このサービスの一部として渡された最初の初期化データを格納するバイト配列<see cref="T:System.Fabric.Description.ServiceDescription" />です。</para>
        </param>
        <param name="partitionId">
          <para>パーティション ID (GUID) このレプリカが関連付けられています。 </para>
        </param>
        <param name="instanceId">
          <para>型のこのレプリカに対してレプリカ ID<see cref="T:System.Int64" />です。</para>
        </param>
        <summary>
          <para>特定のサービスのステートレス サービス インスタンスを作成します。 このメソッドは、Service Fabric によって呼び出されます。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IStatelessServiceInstance" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>