<Type Name="TestScenarioParameters" FullName="System.Fabric.Testability.Scenario.TestScenarioParameters">
  <TypeSignature Language="C#" Value="public abstract class TestScenarioParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit TestScenarioParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestScenarioParameters" />
  <TypeSignature Language="F#" Value="type TestScenarioParameters = class" />
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
            <span data-ttu-id="b31ac-101">パラメーターの基本クラスは、すべての共通パラメーターを定義するすべての TestScenarios に渡されます。</span><span class="sxs-lookup"><span data-stu-id="b31ac-101">Base class for parameters passed into all the TestScenarios which defines all the common parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal TestScenarioParameters (TimeSpan timetoRun);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan timetoRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenarioParameters.#ctor(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (timetoRun As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.TestScenarioParameters : TimeSpan -&gt; System.Fabric.Testability.Scenario.TestScenarioParameters" Usage="new System.Fabric.Testability.Scenario.TestScenarioParameters timetoRun" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timetoRun" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timetoRun"><span data-ttu-id="b31ac-102">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="b31ac-102">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="b31ac-103">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="b31ac-103">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToRun">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToRun" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.TestScenarioParameters.TimeToRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToRun As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToRun : TimeSpan" Usage="System.Fabric.Testability.Scenario.TestScenarioParameters.TimeToRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31ac-104">終了する前に、シナリオを実行する時間の合計。</span><span class="sxs-lookup"><span data-stu-id="b31ac-104">Total time for which the scenario will run before ending.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b31ac-105">TimeSpan としてシナリオの最大実行時間を返します</span><span class="sxs-lookup"><span data-stu-id="b31ac-105">Returns the max run-time of the scenario as TimeSpan</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenFaults">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.TestScenarioParameters.WaitTimeBetweenFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenFaults As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenFaults : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.TestScenarioParameters.WaitTimeBetweenFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31ac-106">待機連続する障害の間の時間の上限: 値が大きいほど、低く (エラー) の同時実行します。</span><span class="sxs-lookup"><span data-stu-id="b31ac-106">The maximum wait time between consecutive faults: the larger the value, the lower the concurrency (of faults).</span></span>
            </summary>
        <value>
            <span data-ttu-id="b31ac-107">TimeSpan として 2 つの連続する障害の間の最大待機時間を返します。</span><span class="sxs-lookup"><span data-stu-id="b31ac-107">Returns the maximum wait time between two consecutive faults as a TimeSpan</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenFaultsDefault">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan WaitTimeBetweenFaultsDefault;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan WaitTimeBetweenFaultsDefault" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Testability.Scenario.TestScenarioParameters.WaitTimeBetweenFaultsDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly WaitTimeBetweenFaultsDefault As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable WaitTimeBetweenFaultsDefault : TimeSpan" Usage="System.Fabric.Testability.Scenario.TestScenarioParameters.WaitTimeBetweenFaultsDefault" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31ac-108">WaitTimeBetweenFaults の既定値は、ユーザーによって値が指定されていない場合に使用します。</span><span class="sxs-lookup"><span data-stu-id="b31ac-108">Default value for WaitTimeBetweenFaults used if value not specified by user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>