<Type Name="ReplicaLoadInformation" FullName="System.Fabric.Query.ReplicaLoadInformation">
  <TypeSignature Language="C#" Value="public class ReplicaLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReplicaLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicaLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicaLoadInformation" />
  <TypeSignature Language="F#" Value="type ReplicaLoadInformation = class" />
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
      <para>レプリカの負荷メトリック情報を格納するデータ構造を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ReplicaLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.ReplicaLoadInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMetricReports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; LoadMetricReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; LoadMetricReports" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicaLoadInformation.LoadMetricReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadMetricReports As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.LoadMetricReports : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.ReplicaLoadInformation.LoadMetricReports" />
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
          <para>レプリカのメトリックとその負荷の一覧を取得します。</para>
        </summary>
        <value>
          <para>メトリックとレプリカの負荷の一覧。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicaLoadInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.ReplicaLoadInformation.PartitionId" />
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
          <para>パーティション識別子を取得します。</para>
        </summary>
        <value>
          <para>パーティションの識別子。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicaLoadInformation.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.Query.ReplicaLoadInformation.ReplicaOrInstanceId" />
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
          <para>レプリカの取得識別子 (ステートフル サービス)、または instanceId (ステートレス サービス)。</para>
        </summary>
        <value>
          <para>レプリカ識別子 (ステートフル サービス)、または instanceId (ステートレス サービス)。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>