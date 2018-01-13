<Type Name="RemoteReplicatorAcknowledgementStatus" FullName="System.Fabric.Query.RemoteReplicatorAcknowledgementStatus">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorAcknowledgementStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorAcknowledgementStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorAcknowledgementStatus" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorAcknowledgementStatus = class" />
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
            コピーとレプリケーション ストリームの受信確認の詳細を提供します。 メンバー<see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorAcknowledgementStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyStreamAcknowledgementDetail">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.RemoteReplicatorAcknowledgementDetail CopyStreamAcknowledgementDetail { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.RemoteReplicatorAcknowledgementDetail CopyStreamAcknowledgementDetail" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus.CopyStreamAcknowledgementDetail" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyStreamAcknowledgementDetail As RemoteReplicatorAcknowledgementDetail" />
      <MemberSignature Language="F#" Value="member this.CopyStreamAcknowledgementDetail : System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementStatus.CopyStreamAcknowledgementDetail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.RemoteReplicatorAcknowledgementDetail</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コピー操作のストリームの受信確認に関する詳細情報が含まれています
            </summary>
        <value>
          <para>コピー操作のストリームの RemoteReplicatorAcknowledgementDetail オブジェクトを返します。 詳細については、「 <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" /> 」を参照してください。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationStreamAcknowledgementDetail">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.RemoteReplicatorAcknowledgementDetail ReplicationStreamAcknowledgementDetail { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.RemoteReplicatorAcknowledgementDetail ReplicationStreamAcknowledgementDetail" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus.ReplicationStreamAcknowledgementDetail" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationStreamAcknowledgementDetail As RemoteReplicatorAcknowledgementDetail" />
      <MemberSignature Language="F#" Value="member this.ReplicationStreamAcknowledgementDetail : System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementStatus.ReplicationStreamAcknowledgementDetail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.RemoteReplicatorAcknowledgementDetail</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリケーション操作のストリームの受信確認に関する詳細情報が含まれています
            </summary>
        <value>
          <para>レプリケーション操作のストリームの RemoteReplicatorAcknowledgementDetail オブジェクトを返します。 詳細については、「 <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" /> 」を参照してください。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>