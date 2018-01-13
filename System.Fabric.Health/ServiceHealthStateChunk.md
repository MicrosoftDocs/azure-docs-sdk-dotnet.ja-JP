<Type Name="ServiceHealthStateChunk" FullName="System.Fabric.Health.ServiceHealthStateChunk">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateChunk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateChunk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateChunk" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateChunk" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateChunk = class" />
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
            基本的な正常性サービスの情報が含まれているサービスの正常性の状態チャンクを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.ServiceHealthStateChunk.HealthState" />
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
            報告された状態のすべてのイベント、その子およびアプリケーションの正常性ポリシーに基づく計算、サービスの集計されたヘルス状態を取得します。
            </summary>
        <value>サービスの集計された正常性状態</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionHealthStateChunks">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStateChunkList PartitionHealthStateChunks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStateChunkList PartitionHealthStateChunks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.PartitionHealthStateChunks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionHealthStateChunks As PartitionHealthStateChunkList" />
      <MemberSignature Language="F#" Value="member this.PartitionHealthStateChunks : System.Fabric.Health.PartitionHealthStateChunkList" Usage="System.Fabric.Health.ServiceHealthStateChunk.PartitionHealthStateChunks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStateChunkList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            入力のフィルターの適用状態チャンク サービス パーティションの正常性の一覧を取得します。
            </summary>
        <value>入力フィルターを適用するパーティションのヘルス状態のチャンクの一覧。</value>
        <remarks>
          <para>既定では、子ない結果に含められます。 ユーザーは、必要な正常性アドインまたはその他の情報に基づく子の一部を含めるように要求できます。 たとえば、ユーザーは、ヘルス状態のエラーのあるすべてのパーティションを含めるに要求できます。
            フィルター値に関係なく、すべての子は、サービスの集計された正常性が計算に使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateChunk.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealthStateChunk.ServiceName" />
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
            サービスを一意に識別するサービス名を取得します。
            </summary>
        <value>サービスの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateChunk.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateChunk.ToString " />
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
            サービスのヘルス状態のチャンクについて説明する文字列を作成します。
            </summary>
        <returns>ヘルス状態のチャンクの説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>