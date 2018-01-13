<Type Name="PartitionHealthStateFilter" FullName="System.Fabric.Health.PartitionHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateFilter = class" />
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
            フィルター処理<see cref="T:System.Fabric.Health.PartitionHealthState" />オブジェクト。
            </summary>
    <remarks>正常性の状態のチャンク クエリは、粒度が細かいパーティション フィルターの一覧は、クエリ結果に含める必要があるパーティションを選択して指定できます。
            渡されるフィルターに関係なく、正常性状態を集計すべてのパーティションが親の評価に使用されることに注意してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.PartitionHealthState" />コレクション内のエントリ。 
            </summary>
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.PartitionHealthState" />コレクション内のエントリ。</value>
        <remarks>ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 フィルターに一致するパーティションの集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdFilter">
      <MemberSignature Language="C#" Value="public Guid PartitionIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionIdFilter As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionIdFilter : Guid with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
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
            取得または、パーティション id フィルターを設定します。
            </summary>
        <value>パーティション id フィルターです。</value>
        <remarks>いない場合は、指定すると、親に一致するすべてのパーティションをフィルター処理 (もしあれば) し、指定したヘルス状態のフィルターはフィルターに一致します。
            それ以外の場合、フィルターは、パーティション id によって識別されるパーティションにのみ適用されます。すべての他のメンバーのフィルター、ヘルス状態のフィルターおよびレプリカ フィルターと同様には、このパーティションに適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaFilters As IList(Of ReplicaHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ReplicaFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;" Usage="System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />をレプリカの子の正常性状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />をレプリカの子の正常性状態に適用できます。</value>
        <remarks>フィルターに一致するすべてのレプリカ子は、パーティションの子として返されます。
            空の場合、既定では子は返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateFilter.ToString " />
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
            フィルターの文字列表現を返します。
            </summary>
        <returns>フィルターの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>