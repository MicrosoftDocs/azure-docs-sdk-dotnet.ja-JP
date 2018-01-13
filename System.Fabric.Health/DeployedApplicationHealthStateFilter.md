<Type Name="DeployedApplicationHealthStateFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateFilter = class" />
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
            フィルター処理<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />オブジェクト。
            </summary>
    <remarks>正常性の状態のチャンクのクエリでは、粒度が細かいに展開済みアプリケーション フィルターの一覧クエリ結果に含める必要がある配置済みアプリケーションの選択を指定できます。
            渡されるフィルターに関係なく、正常性状態を集計すべて配置されているアプリケーションは、親の評価に使用されることに注意してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackageFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageFilters As IList(Of DeployedServicePackageHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />をデプロイ済みサービス パッケージのヘルス状態に適用できます。
            </summary>
        <value>一連の<see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />をデプロイ済みサービス パッケージのヘルス状態に適用できます。</value>
        <remarks>すべては、フィルターに一致するパッケージは、展開されたアプリケーションの子として返されるサービスを配置します。
            空の場合、既定では子は返されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
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
            取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />コレクション内のエントリ。 
            </summary>
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />コレクション内のエントリ。</value>
        <remarks>ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 フィルターの一致するように配置されたアプリケーション、集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeNameFilter">
      <MemberSignature Language="C#" Value="public string NodeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.NodeNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
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
            取得またはノード名のフィルターを設定します。
            </summary>
        <value>ノード名のフィルターです。</value>
        <remarks>以外の場合 (ある場合)、親フィルターに一致する指定すると、展開済みのすべてのアプリケーションが考慮され、その他のメンバーのフィルター選択、ヘルス状態のフィルターと同様に一致しました。
            それ以外の場合、フィルターは、指定したノードにデプロイされたアプリケーションにのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateFilter.ToString " />
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