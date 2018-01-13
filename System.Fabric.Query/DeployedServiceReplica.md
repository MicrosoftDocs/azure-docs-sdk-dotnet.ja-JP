<Type Name="DeployedServiceReplica" FullName="System.Fabric.Query.DeployedServiceReplica">
  <TypeSignature Language="C#" Value="public abstract class DeployedServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit DeployedServiceReplica extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class DeployedServiceReplica" />
  <TypeSignature Language="F#" Value="type DeployedServiceReplica = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatefulServiceReplica))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatelessServiceInstance))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>ノード上のレプリカのビューを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal DeployedServiceReplica (System.Fabric.Query.ServiceKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplica.#ctor(System.Fabric.Query.ServiceKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (kind As ServiceKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.DeployedServiceReplica : System.Fabric.Query.ServiceKind -&gt; System.Fabric.Query.DeployedServiceReplica" Usage="new System.Fabric.Query.DeployedServiceReplica kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Query.ServiceKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>サービスの種類。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Query.DeployedServiceReplica" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.Query.DeployedServiceReplica.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Open または ChangeRole 内のレプリカによって返される最後のアドレス。</para>
        </summary>
        <value>
          <para>Open または ChangeRole 内のレプリカによって返される最後のアドレス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedServiceReplica.CodePackageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このレプリカをホストするコード パッケージの名前。</para>
        </summary>
        <value>
          <para>このレプリカをホストするコード パッケージの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostProcessId">
      <MemberSignature Language="C#" Value="public long HostProcessId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HostProcessId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.HostProcessId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostProcessId As Long" />
      <MemberSignature Language="F#" Value="member this.HostProcessId : int64" Usage="System.Fabric.Query.DeployedServiceReplica.HostProcessId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ホスト プロセス id。</para>
          <value>レプリカがダウンした場合は、0 になります。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partitionid">
      <MemberSignature Language="C#" Value="public Guid Partitionid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Partitionid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.Partitionid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Partitionid As Guid" />
      <MemberSignature Language="F#" Value="member this.Partitionid : Guid" Usage="System.Fabric.Query.DeployedServiceReplica.Partitionid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この replia のパーティションの id。</para>
        </summary>
        <value>
          <para>この replia のパーティションの id。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ServiceReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ServiceReplicaStatus" Usage="System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカの状態です。</para>
        </summary>
        <value>
          <para>レプリカの状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカ (ステートフルまたはステートレス) の型。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Query.ServiceKind" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceManifestName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このレプリカをホストしているコード パッケージを含むサービス パッケージの名前。</para>
        </summary>
        <value>
          <para><see cref="T:System.String" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceManifestVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is no longer supported", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス マニフェストのバージョン。</para>
        </summary>
        <value>
          <para>サービス マニフェストのバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの名前。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス パッケージの ActivationId します。
            </summary>
        <value>
          <para>
            展開済みサービス パッケージの ActivationId を表す文字列。 場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
          <remarks>
            場合は、null 値を持つこのできます<see cref="P:System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" />以外の場合は、 <see cref="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />、<see cref="F:System.Fabric.Query.ServiceReplicaStatus.Standby" />または<see cref="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />です。
            </remarks>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの種類の名前。</para>
        </summary>
        <value>
          <para>サービスの種類の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>