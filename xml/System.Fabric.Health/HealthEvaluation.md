<Type Name="HealthEvaluation" FullName="System.Fabric.Health.HealthEvaluation">
  <TypeSignature Language="C#" Value="public abstract class HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HealthEvaluation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HealthEvaluation" />
  <TypeSignature Language="F#" Value="type HealthEvaluation = class" />
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
      <para><span data-ttu-id="2afb2-101">データとエンティティのヘルスを評価する正常性ストアによって使用されるアルゴリズムを記述する正常性評価を表します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-101">Represents a health evaluation which describes the data and the algorithm used by health store to evaluate the health of an entity.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthEvaluation (System.Fabric.Health.HealthEvaluationKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Health.HealthEvaluationKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvaluation.#ctor(System.Fabric.Health.HealthEvaluationKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As HealthEvaluationKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthEvaluation : System.Fabric.Health.HealthEvaluationKind -&gt; System.Fabric.Health.HealthEvaluation" Usage="new System.Fabric.Health.HealthEvaluation kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Health.HealthEvaluationKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para><span data-ttu-id="2afb2-102"><see cref="T:System.Fabric.Health.HealthEvaluationKind" />評価します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-102">The <see cref="T:System.Fabric.Health.HealthEvaluationKind" /> of the evaluation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2afb2-103"><see cref="T:System.Fabric.Health.HealthEvaluation" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthEvaluation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthEvaluation.AggregatedHealthState" />
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
          <para><span data-ttu-id="2afb2-104">評価されたエンティティの集計された正常性状態です。</span><span class="sxs-lookup"><span data-stu-id="2afb2-104">The aggregated health state of the evaluated entity.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2afb2-105">A<see cref="T:System.Fabric.Health.HealthState" />集計された正常性の状態を表すです。</span><span class="sxs-lookup"><span data-stu-id="2afb2-105">A <see cref="T:System.Fabric.Health.HealthState" /> representing the aggregated health state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="System.Fabric.Health.HealthEvaluation.Description" />
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
          <para><span data-ttu-id="2afb2-106">評価プロセスの概要を表す正常性評価の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-106">Gets the description of the health evaluation, which represents a summary of the evaluation process.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2afb2-107">A<see cref="T:System.String" />正常性評価の説明を表すです。</span><span class="sxs-lookup"><span data-stu-id="2afb2-107">A <see cref="T:System.String" /> representing the description of the health evaluation.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEvaluationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthEvaluationKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As HealthEvaluationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Health.HealthEvaluationKind" Usage="System.Fabric.Health.HealthEvaluation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEvaluationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2afb2-108">正常性評価の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-108">Gets the kind of the health evaluation.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2afb2-109">A<see cref="T:System.Fabric.Health.HealthEvaluationKind" />の正常性評価します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-109">A <see cref="T:System.Fabric.Health.HealthEvaluationKind" /> of the health evaluation.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvaluation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvaluation.ToString " />
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
            <span data-ttu-id="2afb2-110">正常性評価の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="2afb2-110">Returns a string representation of the health evaluation.</span></span>
            </summary>
        <returns><span data-ttu-id="2afb2-111">正常性評価の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="2afb2-111">A string representation of the health evaluation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>