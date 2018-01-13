<Type Name="JobConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.JobConstraints">
  <TypeSignature Language="C#" Value="public class JobConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobConstraints" />
  <TypeSignature Language="F#" Value="type JobConstraints = class" />
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
            ジョブの実行制約。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor" />
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
            JobConstraints クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobConstraints (maxWallClockTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime">ジョブの実行は、最大の経過時間は、ジョブが作成された時点から計測されます。</param>
        <param name="maxTaskRetryCount">各タスクが再試行される最大回数。 Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。</param>
        <summary>
            JobConstraints クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxTaskRetryCount" />
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
            取得または、各タスクが再試行される最大回数を設定します。
            Batch サービスは、終了コードが 0 以外の場合にタスクを再試行します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この値によって再試行の回数が限定されますのでご注意ください。
            バッチ サービスでは、タスクごとに 1 回試みます、可能性があります、この上限に達するまで再試行してください。 たとえば、最大再試行回数が 3 の場合、Batch はタスクを最大 4 回試行します (初回試行 1 回と再試行 3 回)。 最大再試行回数が 0 の場合、Batch サービスはタスクを再試行しません。
            最大再試行回数が -1 の場合、Batch サービスはタスクを無制限に再試行します。 既定値は 0 (再試行なし) です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobConstraints.MaxWallClockTime" />
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
            取得またはジョブが作成された時点から計測されます、ジョブに実行できる最大経過時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            制限時間内にジョブが完了しない場合、Batch service は、まだ実行しているすべてのタスクを終了します。 この場合、MaxWallClockTimeExpiry 終了の理由になります。 このプロパティが指定されていない場合がある制限はありません時間、ジョブの実行がどのくらいの時間です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>