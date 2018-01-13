<Type Name="ServicePartitionResolutionChangeHandler" FullName="System.Fabric.ServicePartitionResolutionChangeHandler">
  <TypeSignature Language="C#" Value="public delegate void ServicePartitionResolutionChangeHandler(FabricClient source, long handlerId, ServicePartitionResolutionChange args);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePartitionResolutionChangeHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChangeHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub ServicePartitionResolutionChangeHandler(source As FabricClient, handlerId As Long, args As ServicePartitionResolutionChange)" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChangeHandler = delegate of FabricClient * int64 * ServicePartitionResolutionChange -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Fabric.FabricClient" />
    <Parameter Name="handlerId" Type="System.Int64" />
    <Parameter Name="args" Type="System.Fabric.ServicePartitionResolutionChange" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source">
      <para>参照、<see cref="T:System.Fabric.FabricClient" />インスタンス エンドポイントの受信イベントに変更します。</para>
    </param>
    <param name="handlerId">
      <para>返される ID<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />ハンドラーの登録時にします。</para>
    </param>
    <param name="args">
      <para>イベントの詳細を含むイベント引数。 <seealso cref="T:System.Fabric.ServicePartitionResolutionChange" /></para>
    </param>
    <summary>
      <para>クライアント側のコールバック サービスの変更、または例外のエンドポイントが実行時にエンドポイント情報を更新するプロセス中に発生したときに、ユーザー コードに加えられたのデリゲート型です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>