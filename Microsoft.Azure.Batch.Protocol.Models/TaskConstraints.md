<Type Name="TaskConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints">
  <TypeSignature Language="C#" Value="public class TaskConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskConstraints" />
  <TypeSignature Language="F#" Value="type TaskConstraints = class" />
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
            タスクに適用する制約を実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TaskConstraints クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional retentionTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints (maxWallClockTime, retentionTime, maxTaskRetryCount)" />
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
        <param name="maxWallClockTime">タスクの開始時点からタスクを実行できる最大経過時間が計測されます。 制限時間内にタスクが完了しない場合、Batch service によって終了します。</param>
        <param name="retentionTime">行く先、実行が完了した時点から、コンピューティング ノード上の作業ディレクトリを保持する最小期間。 この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。</param>
        <param name="maxTaskRetryCount">タスクを再試行できる最大回数。 Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。</param>
        <summary>
            TaskConstraints クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、タスクが再試行される最大回数を設定します。
            Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この値によって再試行の回数が限定されますのでご注意ください。
            Batch サービスはタスクを 1 回試行してから、上限に達するまで再試行できます。 たとえば、最大再試行回数が 3 の場合は、バッチを試みるタスクには最大 4 倍 (最初の試行が 1 回と 3 回)。 最大再試行回数が 0 の場合、Batch service は、タスクを再試行しません。 最大再試行回数場合は-1、バッチ サービスの再試行制限がないタスクです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの開始時点から計測されます、タスクに実行できる最大経過時間を設定します。 制限時間内にタスクが完了しない場合、Batch service によって終了します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これが指定されていない場合いない時間に制限はタスクの実行がどのくらいの時間です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または行く先、実行が完了した時点から、コンピューティング ノード上の作業ディレクトリを保持する時間の最小値を設定します。
            この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値が有限、コンピューティング ノードが削除または再イメージ化されるまでに、作業ディレクトリを保持するなどです。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>