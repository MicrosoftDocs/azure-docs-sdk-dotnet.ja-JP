<Type Name="PartitionHealthStateChunk" FullName="System.Fabric.Health.PartitionHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateChunk" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateChunk = class" />
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
            パーティションに関する基本的な正常性の情報が含まれているパーティションの正常性の状態チャンクを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.PartitionHealthStateChunk.HealthState" />
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
            パーティションの集計計算のヘルス状態の取得は、報告された状態のすべてのイベント、レプリカの子およびアプリケーションの正常性ポリシーに基づいています。
            </summary>
        <value>パーティションの集計された正常性状態</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthStateChunk.PartitionId" />
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
            パーティション id を取得します。
            </summary>
        <value>パーティション id。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStateChunkList ReplicaHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaHealthStateChunks As ReplicaHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.ReplicaHealthStateChunks : System.Fabric.Health.ReplicaHealthStateChunkList" Usage="System.Fabric.Health.PartitionHealthStateChunk.ReplicaHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリカのヘルス状態チャンク入力フィルターを適用するパーティションの一覧を取得します。
            </summary>
        <value>入力フィルターを適用するパーティション レプリカ ヘルス状態チャンクの一覧。</value>
        <remarks>
          <para>既定では、子ない結果に含められます。 ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。 たとえば、ユーザーは、ヘルス状態のエラーのあるすべてのレプリカを含めるに要求できます。
            フィルター値に関係なく、すべての子は、パーティションの集計された正常性が計算に使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateChunk.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            パーティションのヘルス状態のチャンクについて説明する文字列を作成します。
            </summary>
        <returns>ヘルス状態のチャンクの説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>