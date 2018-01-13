<Type Name="Partition" FullName="System.Fabric.Query.Partition">
  <TypeSignature Language="C#" Value="public abstract class Partition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Partition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Partition" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Partition" />
  <TypeSignature Language="F#" Value="type Partition = class" />
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
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessServicePartition))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulServicePartition))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>パーティションを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Partition (System.Fabric.Query.ServiceKind serviceKind, System.Fabric.ServicePartitionInformation partitionInformation, System.Fabric.Health.HealthState healthState, System.Fabric.Query.ServicePartitionStatus partitionStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind, class System.Fabric.ServicePartitionInformation partitionInformation, valuetype System.Fabric.Health.HealthState healthState, valuetype System.Fabric.Query.ServicePartitionStatus partitionStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.Partition.#ctor(System.Fabric.Query.ServiceKind,System.Fabric.ServicePartitionInformation,System.Fabric.Health.HealthState,System.Fabric.Query.ServicePartitionStatus)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.Partition : System.Fabric.Query.ServiceKind * System.Fabric.ServicePartitionInformation * System.Fabric.Health.HealthState * System.Fabric.Query.ServicePartitionStatus -&gt; System.Fabric.Query.Partition" Usage="new System.Fabric.Query.Partition (serviceKind, partitionInformation, healthState, partitionStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
        <Parameter Name="partitionInformation" Type="System.Fabric.ServicePartitionInformation" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
        <Parameter Name="partitionStatus" Type="System.Fabric.Query.ServicePartitionStatus" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para>パーティションの種類</para>
        </param>
        <param name="partitionInformation">
          <para>パーティション情報</para>
        </param>
        <param name="healthState">
          <para>パーティションの正常性状態</para>
        </param>
        <param name="partitionStatus">
          <para>パーティションの状態</para>
        </param>
        <summary>
          <para>パーティションの新しいインスタンスを初期化します</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Partition.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>パーティションのヘルス状態を取得します。</para>
        </summary>
        <value>
          <para>パーティションの正常性状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.PartitionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInformation As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInformation : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.Query.Partition.PartitionInformation" />
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
          <para>パーティション情報を取得します。</para>
        </summary>
        <value>
          <para>パーティションの情報です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServicePartitionStatus PartitionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServicePartitionStatus PartitionStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.PartitionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionStatus As ServicePartitionStatus" />
      <MemberSignature Language="F#" Value="member this.PartitionStatus : System.Fabric.Query.ServicePartitionStatus" Usage="System.Fabric.Query.Partition.PartitionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>パーティションの状態を取得します。</para>
        </summary>
        <value>
          <para>パーティションの状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Partition.ServiceKind" />
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
          <para>パーティション (ステートフル/ステートレス) の種類</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Query.ServiceKind" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>