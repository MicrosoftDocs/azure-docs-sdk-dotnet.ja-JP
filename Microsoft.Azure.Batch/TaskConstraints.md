<Type Name="TaskConstraints" FullName="Microsoft.Azure.Batch.TaskConstraints">
  <TypeSignature Language="C#" Value="public class TaskConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskConstraints" />
  <TypeSignature Language="F#" Value="type TaskConstraints = class&#xA;    interface ITransportObjectProvider&lt;TaskConstraints&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            特定の Azure Batch タスク上の制約を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional retentionTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.TaskConstraints" Usage="new Microsoft.Azure.Batch.TaskConstraints (maxWallClockTime, retentionTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime">タスクの開始時点からタスクを実行できる最大経過時間が計測されます。</param>
        <param name="retentionTime">行く先、実行が完了した時点から、コンピューティング ノード上のタスクの作業ディレクトリを保持する最小期間。 この時刻より後は、作業ディレクトリとその内容をすべて、バッチ サービスは削除できます。</param>
        <param name="maxTaskRetryCount">タスクの再試行の最大数。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.TaskConstraints" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの再試行の最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.MaxWallClockTime" />
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
            取得またはタスクの開始時点から計測されます、タスクに実行できる最大経過時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskConstraints.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskConstraints.RetentionTime" />
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
            取得または行く先、実行が完了した時点から、コンピューティング ノード上のタスクの作業ディレクトリを保持する時間の最小値を設定します。 この時刻より後は、作業ディレクトリとその内容をすべて、バッチ サービスは削除できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>