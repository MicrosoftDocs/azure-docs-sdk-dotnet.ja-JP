<Type Name="DeployedStatefulServiceReplica" FullName="System.Fabric.Query.DeployedStatefulServiceReplica">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplica : System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplica extends System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplica&#xA;Inherits DeployedServiceReplica" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplica = class&#xA;    inherit DeployedServiceReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplica</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>展開済みのステートフル サービス レプリカを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplica ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplica.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.DeployedStatefulServiceReplica" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationInformation ReconfigurationInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReconfigurationInformation ReconfigurationInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReconfigurationInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationInformation As ReconfigurationInformation" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationInformation : System.Fabric.ReconfigurationInformation" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReconfigurationInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>前の構成のロール、再構成の種類、再構成フェーズおよび再構成開始日時と同じように、現在の再構成に関する追加情報を取得します。</para>
          <value>再構成情報です。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaId" />
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
          <para>レプリカ ID を取得します</para>
        </summary>
        <value>
          <para>レプリカ ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRole">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicaRole ReplicaRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReplicaRole ReplicaRole" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaRole As ReplicaRole" />
      <MemberSignature Language="F#" Value="member this.ReplicaRole : System.Fabric.ReplicaRole" Usage="System.Fabric.Query.DeployedStatefulServiceReplica.ReplicaRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicaRole</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>現在のレプリカのロールを取得します。</para>
        </summary>
        <value>
          <para>レプリカのロール。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>