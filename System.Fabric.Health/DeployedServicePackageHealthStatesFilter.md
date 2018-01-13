<Type Name="DeployedServicePackageHealthStatesFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStatesFilter = class" />
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
      <para>フィルターを表す<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />オブジェクト。</para>
    </summary>
    <remarks>使用できるフィルター<see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />の一部として返される子展開済みサービス パッケージを指定する<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Use HealthStateFilterValue instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>推奨されなくなりました。 取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。 メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</para>
        </summary>
        <value>
          <para>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。</para>
        </value>
        <remarks>このプロパティは今後使用しません。 代わりに、<see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" /> を使用してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStatesFilter.HealthStateFilterValue" />
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
        <value>集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />エントリです。</value>
        <remarks>入力のコレクションは、必要な正常性状態を尊重エントリのみを返すフィルターされています。 フィルターは、メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStatesFilter.ToString " />
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