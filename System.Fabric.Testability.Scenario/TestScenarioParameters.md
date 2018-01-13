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
            パラメーターの基本クラスは、すべての共通パラメーターを定義するすべての TestScenarios に渡されます。
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
        <param name="timetoRun">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</param>
        <summary>
            この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。
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
            終了する前に、シナリオを実行する時間の合計。
            </summary>
        <value>
            TimeSpan としてシナリオの最大実行時間を返します
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
            待機連続する障害の間の時間の上限: 値が大きいほど、低く (エラー) の同時実行します。
            </summary>
        <value>
            TimeSpan として 2 つの連続する障害の間の最大待機時間を返します。
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
            WaitTimeBetweenFaults の既定値は、ユーザーによって値が指定されていない場合に使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>