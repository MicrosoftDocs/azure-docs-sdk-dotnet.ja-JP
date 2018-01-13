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
      <para><span data-ttu-id="4a9a2-101">正常性評価を表す、<see cref="T:System.Fabric.Health.HealthEvent" />です。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-101">Represents health evaluation of a <see cref="T:System.Fabric.Health.HealthEvent" />.</span></span> <span data-ttu-id="4a9a2-102">返されるエンティティのヘルスを評価するときに返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-102">Can be returned when evaluating health of an entity returns <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
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
          <para><span data-ttu-id="4a9a2-103">取得<see cref="T:System.Boolean" />警告をエラーとして重大度が同じで扱われるかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-103">Gets <see cref="T:System.Boolean" /> that indicates whether warnings are treated with the same severity as errors.</span></span> <span data-ttu-id="4a9a2-104">フィールドは、エンティティの評価に使用される正常性ポリシーで指定されます。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-104">The field is specified in the health policy used to evaluate the entity.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="4a9a2-105"><languageKeyword>true</languageKeyword>警告として扱う場合はエラーです。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-105"><languageKeyword>true</languageKeyword> if warnings are treated as errors; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
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
          <para><span data-ttu-id="4a9a2-106">異常なイベントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-106">Gets the unhealthy event details.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4a9a2-107"><see cref="T:System.Fabric.Health.HealthEvent" />現在集計された正常性状態を引き起こしたです。</span><span class="sxs-lookup"><span data-stu-id="4a9a2-107">The <see cref="T:System.Fabric.Health.HealthEvent" /> that led to current aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>