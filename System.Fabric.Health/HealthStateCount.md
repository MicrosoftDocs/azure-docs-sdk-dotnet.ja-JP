<Type Name="HealthStateCount" FullName="System.Fabric.Health.HealthStateCount">
  <TypeSignature Language="C#" Value="public sealed class HealthStateCount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthStateCount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStateCount" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthStateCount" />
  <TypeSignature Language="F#" Value="type HealthStateCount = class" />
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
      <para><span data-ttu-id="72c41-101">正常性エンティティの数についての情報を表す<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。</span><span class="sxs-lookup"><span data-stu-id="72c41-101">Represents information about how many health entities are in <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" />, and <see cref="F:System.Fabric.Health.HealthState.Error" /> state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ErrorCount">
      <MemberSignature Language="C#" Value="public long ErrorCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ErrorCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateCount.ErrorCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCount As Long" />
      <MemberSignature Language="F#" Value="member this.ErrorCount : int64" Usage="System.Fabric.Health.HealthStateCount.ErrorCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72c41-102">ヘルス状態にあるエンティティの数を取得<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-102">Gets the number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            </summary>
        <value>
            <span data-ttu-id="72c41-103">エンティティのヘルス状態にある数<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-103">The number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OkCount">
      <MemberSignature Language="C#" Value="public long OkCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OkCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateCount.OkCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OkCount As Long" />
      <MemberSignature Language="F#" Value="member this.OkCount : int64" Usage="System.Fabric.Health.HealthStateCount.OkCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72c41-104">ヘルス状態にあるエンティティの数を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-104">Gets the number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span>
            </summary>
        <value>
            <span data-ttu-id="72c41-105">エンティティのヘルス状態にある数<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-105">The number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthStateCount.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthStateCount.ToString " />
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
            <span data-ttu-id="72c41-106">ヘルス状態の数の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="72c41-106">Returns a string representation of the health state count.</span></span>
            </summary>
        <returns><span data-ttu-id="72c41-107">ヘルス状態の数の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="72c41-107">A string representation of the health state count.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WarningCount">
      <MemberSignature Language="C#" Value="public long WarningCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WarningCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthStateCount.WarningCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WarningCount As Long" />
      <MemberSignature Language="F#" Value="member this.WarningCount : int64" Usage="System.Fabric.Health.HealthStateCount.WarningCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72c41-108">ヘルス状態にあるエンティティの数を取得<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-108">Gets the number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span>
            </summary>
        <value>
            <span data-ttu-id="72c41-109">エンティティのヘルス状態にある数<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="72c41-109">The number of entities that are in health state <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>