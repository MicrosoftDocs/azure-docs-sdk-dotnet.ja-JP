<Type Name="ReconfigurationInformation" FullName="System.Fabric.ReconfigurationInformation">
  <TypeSignature Language="C#" Value="public sealed class ReconfigurationInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReconfigurationInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReconfigurationInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReconfigurationInformation" />
  <TypeSignature Language="F#" Value="type ReconfigurationInformation = class" />
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
            レプリカの再構成についての情報を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReconfigurationInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReconfigurationInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.ReconfigurationInformation" /> クラスの新しいインスタンスを既定値で初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReconfigurationInformation (System.Fabric.ReplicaRole previousConfigurationRole, System.Fabric.ReconfigurationPhase reconfigurationPhase, System.Fabric.ReconfigurationType reconfigurationType, DateTime reconfigurationStartTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.ReplicaRole previousConfigurationRole, valuetype System.Fabric.ReconfigurationPhase reconfigurationPhase, valuetype System.Fabric.ReconfigurationType reconfigurationType, valuetype System.DateTime reconfigurationStartTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReconfigurationInformation.#ctor(System.Fabric.ReplicaRole,System.Fabric.ReconfigurationPhase,System.Fabric.ReconfigurationType,System.DateTime)" />
      <MemberSignature Language="F#" Value="new System.Fabric.ReconfigurationInformation : System.Fabric.ReplicaRole * System.Fabric.ReconfigurationPhase * System.Fabric.ReconfigurationType * DateTime -&gt; System.Fabric.ReconfigurationInformation" Usage="new System.Fabric.ReconfigurationInformation (previousConfigurationRole, reconfigurationPhase, reconfigurationType, reconfigurationStartTimeUtc)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="previousConfigurationRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="reconfigurationPhase" Type="System.Fabric.ReconfigurationPhase" />
        <Parameter Name="reconfigurationType" Type="System.Fabric.ReconfigurationType" />
        <Parameter Name="reconfigurationStartTimeUtc" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="previousConfigurationRole"></param>
        <param name="reconfigurationPhase"></param>
        <param name="reconfigurationType"></param>
        <param name="reconfigurationStartTimeUtc"></param>
        <summary>
          <para><see cref="T:System.Fabric.ReconfigurationInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousConfigurationRole">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicaRole PreviousConfigurationRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReplicaRole PreviousConfigurationRole" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.PreviousConfigurationRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousConfigurationRole As ReplicaRole" />
      <MemberSignature Language="F#" Value="member this.PreviousConfigurationRole : System.Fabric.ReplicaRole" Usage="System.Fabric.ReconfigurationInformation.PreviousConfigurationRole" />
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
          <para>再構成する前に、レプリカのロール。 値になります<see cref="F:System.Fabric.ReplicaRole.Unknown" />以前再構成されていない場合は。</para>
          <value>以前のレプリカのロール。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPhase">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationPhase ReconfigurationPhase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReconfigurationPhase ReconfigurationPhase" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationPhase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationPhase As ReconfigurationPhase" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationPhase : System.Fabric.ReconfigurationPhase" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationPhase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationPhase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>再構成の現在のフェーズです。 値になります<see cref="F:System.Fabric.ReconfigurationPhase.None" />再構成が行われていない場合。</para>
          <value>現在の継続的な再構成のフェーズ。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationStartTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ReconfigurationStartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ReconfigurationStartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationStartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationStartTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationStartTimeUtc : DateTime" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationStartTimeUtc" />
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
          <param>再構成が開始された日時です。 値は、UTC の日時として表されます。 値になる<see cref="F:System.DateTime.MinValue" />再構成が行われていない場合。</param>
          <value>UTC 形式で再構成の日時を開始します。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationType">
      <MemberSignature Language="C#" Value="public System.Fabric.ReconfigurationType ReconfigurationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ReconfigurationType ReconfigurationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReconfigurationInformation.ReconfigurationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReconfigurationType As ReconfigurationType" />
      <MemberSignature Language="F#" Value="member this.ReconfigurationType : System.Fabric.ReconfigurationType" Usage="System.Fabric.ReconfigurationInformation.ReconfigurationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReconfigurationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <param>再構成の型。 値になります<see cref="F:System.Fabric.ReconfigurationType.None" />再構成が行われていない場合。</param>
          <value>再構成の型。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>