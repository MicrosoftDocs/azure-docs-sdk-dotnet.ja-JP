<Type Name="EventHealthEvaluation" FullName="System.Fabric.Health.EventHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class EventHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EventHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type EventHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthEvaluation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>正常性評価を表す、<see cref="T:System.Fabric.Health.HealthEvent" />です。 返されるエンティティのヘルスを評価するときに返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EventHealthEvaluation.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool" Usage="System.Fabric.Health.EventHealthEvaluation.ConsiderWarningAsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得<see cref="T:System.Boolean" />警告をエラーとして重大度が同じで扱われるかどうかを示すです。 フィールドは、エンティティの評価に使用される正常性ポリシーで指定されます。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>警告として扱う場合はエラーです。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvent">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEvent UnhealthyEvent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEvent UnhealthyEvent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EventHealthEvaluation.UnhealthyEvent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvent As HealthEvent" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvent : System.Fabric.Health.HealthEvent" Usage="System.Fabric.Health.EventHealthEvaluation.UnhealthyEvent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEvent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>異常なイベントの詳細を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthEvent" />現在集計された正常性状態を引き起こしたです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>