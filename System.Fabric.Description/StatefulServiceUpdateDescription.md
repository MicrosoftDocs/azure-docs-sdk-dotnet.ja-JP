<Type Name="StatefulServiceUpdateDescription" FullName="System.Fabric.Description.StatefulServiceUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceUpdateDescription : System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceUpdateDescription extends System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceUpdateDescription&#xA;Inherits ServiceUpdateDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceUpdateDescription = class&#xA;    inherit ServiceUpdateDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceUpdateDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>表す、<see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />変更に使用される、<see cref="T:System.Fabric.Description.StatefulServiceDescription" />経由で実行中のサービスの<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />します。 指定したプロパティは、実行中のサービスに適用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />プロパティが設定されていないクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : Nullable&lt;int&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> の <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> を取得または設定します。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> の <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />。</para>
        </value>
        <remarks>
          <para>「<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />」を参照してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> の <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" /> を取得または設定します。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" /> の <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />。</para>
        </value>
        <remarks>
          <para>「<see cref="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />」を参照してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> の <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" /> を取得または設定します。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" /> の <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />。</para>
        </value>
        <remarks>
          <para>「<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />」を参照してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> の <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" /> を取得または設定します。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" /> の <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />。</para>
        </value>
        <remarks>
          <para>「<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />」を参照してください。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : Nullable&lt;int&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> の <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> を取得または設定します。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> の <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />。</para>
        </value>
        <remarks>
          <para>以下を参照してください。<see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>