<Type Name="ServiceHealthStateFilter" FullName="System.Fabric.Health.ServiceHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateFilter = class" />
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
            フィルター処理<see cref="T:System.Fabric.Health.ServiceHealthState" />オブジェクト。
            </summary>
    <remarks>エンティティのヘルス状態のチャンク クエリは、粒度が細かいするサービスのフィルターの一覧は、クエリ結果に含める必要があるサービスを選択して指定できます。
            渡されるフィルターに関係なく、正常性状態を集計、サービスは、親の評価に使用されるすべてことに注意してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
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
            取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。 
            </summary>
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。</value>
        <remarks>ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 フィルターに一致するサービスの集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionFilters As IList(Of PartitionHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.PartitionFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;" Usage="System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />パーティションの子の正常性状態に適用します。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />パーティションの子の正常性状態に適用します。</value>
        <remarks>一覧には、1 つの既定のパーティションのフィルターや、クエリによって返される粒度が細かいエンティティに特定のパーティションのパーティションのフィルターを含めることができます。
            フィルターに一致するすべてのパーティションの子は、サービスの子として返されます。
            空の場合、既定では子は返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
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
            取得またはサービス名のフィルターを設定します。
            </summary>
        <value>サービス名のフィルターです。</value>
        <remarks>指定しない場合、親フィルター (指定されている場合) と指定したヘルス状態のフィルターに一致するすべてのサービスは、フィルターに一致します。
            それ以外の場合、フィルターは、指定されたサービスにのみ適用されます。 すべての他のメンバーのフィルター、ヘルス状態のフィルターと同様には、このサービスに適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateFilter.ToString " />
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