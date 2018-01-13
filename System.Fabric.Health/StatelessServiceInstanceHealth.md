<Type Name="StatelessServiceInstanceHealth" FullName="System.Fabric.Health.StatelessServiceInstanceHealth">
  <TypeSignature Language="C#" Value="public sealed class StatelessServiceInstanceHealth : System.Fabric.Health.ReplicaHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatelessServiceInstanceHealth extends System.Fabric.Health.ReplicaHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.StatelessServiceInstanceHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatelessServiceInstanceHealth&#xA;Inherits ReplicaHealth" />
  <TypeSignature Language="F#" Value="type StatelessServiceInstanceHealth = class&#xA;    inherit ReplicaHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.ReplicaHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>によって返される、ステートレスなインスタンスの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public long InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 InstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.StatelessServiceInstanceHealth.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.InstanceId : int64" Usage="System.Fabric.Health.StatelessServiceInstanceHealth.InstanceId" />
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
          <para>ステートレス サービス インスタンスのインスタンス ID を取得します。</para>
        </summary>
        <value>
          <para>インスタンス ID。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>