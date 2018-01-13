<Type Name="HealthStatistics" FullName="System.Fabric.Health.HealthStatistics">
  <TypeSignature Language="C#" Value="public sealed class HealthStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStatistics" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthStatistics" />
  <TypeSignature Language="F#" Value="type HealthStatistics = class" />
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
      <para>
            エンティティの正常性の統計情報を表します。
            クエリの説明が統計を含める に構成されている場合は、正常性クエリの結果の一部として返されます。
            統計情報には、すべての子の型の現在のエンティティのヘルス状態の数が含まれます。
            たとえば、クラスターの正常性統計にはノード、アプリケーション、サービス、パーティション、レプリカ、展開済みのアプリケーションおよび展開済みサービス パッケージのヘルス状態の数が含まれます。
            パーティションの正常性の統計情報には、レプリカの正常性のカウントが含まれます。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStateCountList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.EntityKindHealthStateCount&gt; HealthStateCountList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStateCountList As IList(Of EntityKindHealthStateCount)" />
      <MemberSignature Language="F#" Value="member this.HealthStateCountList : System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;" Usage="System.Fabric.Health.HealthStatistics.HealthStateCountList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.EntityKindHealthStateCount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:System.Fabric.Health.HealthStateCount" />別のエンティティの種類について説明します。
            </summary>
        <value>使用したリスト<see cref="T:System.Fabric.Health.HealthStateCount" />別のエンティティの種類について説明します。</value>
        <remarks>
          <para>
            一覧の追跡、照会されたエンティティの子供の数が、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStatistics.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthStatistics.ToString " />
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
            ヘルス状態の数の文字列表現を返します。
            </summary>
        <returns>ヘルス状態の数の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>