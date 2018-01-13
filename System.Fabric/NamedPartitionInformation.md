<Type Name="NamedPartitionInformation" FullName="System.Fabric.NamedPartitionInformation">
  <TypeSignature Language="C#" Value="public sealed class NamedPartitionInformation : System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedPartitionInformation extends System.Fabric.ServicePartitionInformation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedPartitionInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedPartitionInformation&#xA;Inherits ServicePartitionInformation" />
  <TypeSignature Language="F#" Value="type NamedPartitionInformation = class&#xA;    inherit ServicePartitionInformation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ServicePartitionInformation</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>パーティション構成に基づいている文字列として、名前のパーティション情報について説明します。
            サービスは、この種類を観察<see cref="T:System.Fabric.ServicePartitionInformation" />でサービスを作成するときに、<see cref="T:System.Fabric.Description.NamedPartitionSchemeDescription" />です。 <see cref="T:System.Fabric.NamedPartitionInformation" />派生した、<see cref="T:System.Fabric.IServicePartition" />インターフェイスは、サービスの一部として、<see cref="T:System.Fabric.IStatefulServicePartition" />または<see cref="T:System.Fabric.IStatelessServicePartition" />インターフェイスをステートフルな時に渡される<see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />ステートレスまたは<see cref="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPartitionInformation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.NamedPartitionInformation.Name" />
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
          <para>サービスのこのパーティションの名前を示します。</para>
        </summary>
        <value>
          <para>サービスのこのパーティションの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>