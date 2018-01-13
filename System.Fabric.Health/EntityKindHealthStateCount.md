<Type Name="EntityKindHealthStateCount" FullName="System.Fabric.Health.EntityKindHealthStateCount">
  <TypeSignature Language="C#" Value="public sealed class EntityKindHealthStateCount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EntityKindHealthStateCount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityKindHealthStateCount" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EntityKindHealthStateCount" />
  <TypeSignature Language="F#" Value="type EntityKindHealthStateCount = class" />
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
            指定されたエンティティの種類のエンティティのヘルス状態の数を表します。
            正常性クエリによって要求されたときの状態の統計の一部として返されます。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EntityKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.EntityKind EntityKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.EntityKind EntityKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityKindHealthStateCount.EntityKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityKind As EntityKind" />
      <MemberSignature Language="F#" Value="member this.EntityKind : System.Fabric.Health.EntityKind" Usage="System.Fabric.Health.EntityKindHealthStateCount.EntityKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.EntityKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンティティの種類を取得します。 <see cref="T:System.Fabric.Health.HealthStateCount" />がこの種類のエンティティの数を示します<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>エンティティの種類。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateCount">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateCount HealthStateCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStateCount HealthStateCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityKindHealthStateCount.HealthStateCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStateCount As HealthStateCount" />
      <MemberSignature Language="F#" Value="member this.HealthStateCount : System.Fabric.Health.HealthStateCount" Usage="System.Fabric.Health.EntityKindHealthStateCount.HealthStateCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateCount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定した種類のエンティティのヘルス状態の数を取得します。
            </summary>
        <value>指定した種類のエンティティのヘルス状態の数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityKindHealthStateCount.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="entityKindHealthStateCount.ToString " />
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