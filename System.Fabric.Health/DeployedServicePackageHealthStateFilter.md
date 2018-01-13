<Type Name="DeployedServicePackageHealthStateFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateFilter = class" />
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
            フィルター処理<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />オブジェクト。
            </summary>
    <remarks>正常性の状態のチャンクのクエリでは、粒度が細かいに展開済みサービス パッケージ フィルターの一覧クエリ結果に含める必要がある展開済みサービス パッケージの選択を指定できます。
            渡されるフィルターに関係なく、正常性状態を集計すべて展開済みサービス パッケージが親の評価に使用されることに注意してください。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
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
            取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。 
            </summary>
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。</value>
        <remarks>ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 展開済みサービス パッケージ フィルターに一致するには、集計された正常性状態は、指定したヘルス状態のフィルターで一致しなければなりません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceManifestNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceManifestNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
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
            取得またはサービス マニフェスト名のフィルターを設定します。
            </summary>
        <value>サービス マニフェスト名のフィルターです。</value>
        <remarks>いない場合は、すべてが指定すると、(存在する場合)、親フィルターに一致するサービス パッケージを配置し、指定したヘルス状態のフィルターはフィルターに一致します。
            それ以外の場合、フィルターは、指定したサービス マニフェスト名を展開済みサービス パッケージにのみ適用され、それと一致するヘルス状態のフィルター。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationIdFilter">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationIdFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationIdFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
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
            取得またはサービス パッケージ ActivationId フィルターを設定します。
            </summary>
        <value>
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービスのパッケージを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
             </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStateFilter.ToString " />
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