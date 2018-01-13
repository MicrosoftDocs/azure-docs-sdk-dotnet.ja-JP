<Type Name="DeployedServiceReplicaDetail" FullName="System.Fabric.Query.DeployedServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public abstract class DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit DeployedServiceReplicaDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedServiceReplicaDetail = class" />
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
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatefulServiceReplicaDetail))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatelessServiceInstanceDetail))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>コード パッケージで実行されているレプリカを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal DeployedServiceReplicaDetail (System.Fabric.Query.ServiceKind serviceKind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaDetail.#ctor(System.Fabric.Query.ServiceKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.DeployedServiceReplicaDetail : System.Fabric.Query.ServiceKind -&gt; System.Fabric.Query.DeployedServiceReplicaDetail" Usage="new System.Fabric.Query.DeployedServiceReplicaDetail serviceKind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para>サービスの種類</para>
        </param>
        <summary>
          <para>
            インスタンスを作成、<see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />指定されたサービスの種類を持つオブジェクト。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceOperationName CurrentServiceOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceOperationName CurrentServiceOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceOperation As ServiceOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceOperation : System.Fabric.Query.ServiceOperationName" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリカで実行されている現在の API 呼び出しを設定します。</para>
        </summary>
        <value>
          <para>レプリカで実行されている現在の API 呼び出し。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceOperationStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime CurrentServiceOperationStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CurrentServiceOperationStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperationStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceOperationStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceOperationStartTimeUtc : DateTime" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.CurrentServiceOperationStartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または UTC 形式で現在のサービス操作の開始時刻を設定します。</para>
        </summary>
        <value>
          <para>UTC 形式で現在のサービス操作の開始時刻です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.PartitionId" />
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
          <para>取得または、このレプリカに関連付けられたパーティション id を設定します。</para>
        </summary>
        <value>
          <para>このレプリカに関連付けられたパーティション id です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportedLoad">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; ReportedLoad { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; ReportedLoad" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ReportedLoad" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReportedLoad As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.ReportedLoad : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ReportedLoad" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または、このレプリカによって報告された負荷を設定します。</para>
        </summary>
        <value>
          <para>このレプリカによって報告されるロードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ServiceKind" />
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
          <para>
            サービスの種類を取得します。 
            </para>
        </summary>
        <value>
          <para>このレプリカが属するサービスの種類を表すサービスの種類</para>
        </value>
        <remarks>
          <para>
            このプロパティの値に基づいてこのオブジェクトは、DeployedStatefulServiceReplicaDetail または DeployedStatelessServiceInstanceDetail downcasted
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaDetail.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Query.DeployedServiceReplicaDetail.ServiceName" />
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
          <para>取得または、このレプリカが属しているサービス名を設定します。</para>
        </summary>
        <value>
          <para>このレプリカが属しているサービス名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>