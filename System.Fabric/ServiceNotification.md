<Type Name="ServiceNotification" FullName="System.Fabric.ServiceNotification">
  <TypeSignature Language="C#" Value="public sealed class ServiceNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceNotification" />
  <TypeSignature Language="F#" Value="type ServiceNotification = class" />
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
      <para>レプリカまたはインスタンス エンドポイントが変更されたサービスに関する詳細を含むサービス通知を表します。 によって通知がディスパッチされます、<see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />イベント。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class System.Fabric.ResolvedServiceEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As ICollection(Of ResolvedServiceEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;" Usage="System.Fabric.ServiceNotification.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.Fabric.ResolvedServiceEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスによって公開された新しいレプリカまたはインスタンスのエンドポイントを取得します。 コレクションは、サービスが削除された場合は、空になります。</para>
        </summary>
        <value>
          <para>サービスによって公開されたエンドポイントの一覧。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceNotification.PartitionId" />
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
          <para>サービスのパーティション ID を取得します。</para>
        </summary>
        <value>
          <para>パーティションの id。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.ServiceNotification.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの詳細なパーティション情報を取得します。 このプロパティは、詳細なパーティション情報を使用できません - サービスの削除イベントがサービス通知イベントした場合など特定の場合は null にすることはできます。</para>
        </summary>
        <value>
          <para>サービスの詳細なパーティション情報。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceNotification.ServiceName" />
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
          <para>サービスの名前を取得します。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public System.Fabric.ServiceEndpointsVersion Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServiceEndpointsVersion Version" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceNotification.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As ServiceEndpointsVersion" />
      <MemberSignature Language="F#" Value="member this.Version : System.Fabric.ServiceEndpointsVersion" Usage="System.Fabric.ServiceNotification.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointsVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この通知イベントのバージョンを取得します。 バージョンは、任意の 2 つの通知イベントの順序を使用できます。</para>
        </summary>
        <value>
          <para>この通知イベントのバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>