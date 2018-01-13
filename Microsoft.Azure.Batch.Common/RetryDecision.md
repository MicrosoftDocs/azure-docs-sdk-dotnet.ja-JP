<Type Name="RetryDecision" FullName="Microsoft.Azure.Batch.Common.RetryDecision">
  <TypeSignature Language="C#" Value="public sealed class RetryDecision" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryDecision extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.RetryDecision" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryDecision" />
  <TypeSignature Language="F#" Value="type RetryDecision = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            によって行われる意思決定を表す、<see cref="T:Microsoft.Azure.Batch.Common.IRetryPolicy" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Common.RetryDecision NoRetry;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Common.RetryDecision NoRetry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.RetryDecision.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoRetry As RetryDecision " />
      <MemberSignature Language="F#" Value=" staticval mutable NoRetry : Microsoft.Azure.Batch.Common.RetryDecision" Usage="Microsoft.Azure.Batch.Common.RetryDecision.NoRetry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RetryDecision</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            再試行の判断を<see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />を false に設定
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RetryDecision.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Batch.Common.RetryDecision.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            次の再試行までの遅延を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryWithDelay">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Common.RetryDecision RetryWithDelay (TimeSpan retryDelay);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Common.RetryDecision RetryWithDelay(valuetype System.TimeSpan retryDelay) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.RetryDecision.RetryWithDelay(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RetryWithDelay (retryDelay As TimeSpan) As RetryDecision" />
      <MemberSignature Language="F#" Value="static member RetryWithDelay : TimeSpan -&gt; Microsoft.Azure.Batch.Common.RetryDecision" Usage="Microsoft.Azure.Batch.Common.RetryDecision.RetryWithDelay retryDelay" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RetryDecision</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="retryDelay">再試行を実行する前に待機する期間です。</param>
        <summary>
            新規作成<see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" />で、次の再試行する前に指定した遅延です。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" />指定された再試行の待ち時間を持つオブジェクトおよび<see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />を true に設定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool" Usage="Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            再試行する必要がありますを実行するかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>