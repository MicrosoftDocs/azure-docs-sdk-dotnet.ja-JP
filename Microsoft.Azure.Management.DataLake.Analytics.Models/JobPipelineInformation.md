<Type Name="JobPipelineInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation">
  <TypeSignature Language="C#" Value="public class JobPipelineInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPipelineInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPipelineInformation" />
  <TypeSignature Language="F#" Value="type JobPipelineInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ジョブ パイプラインについては、パイプラインでのジョブの関係とこれらのジョブを実行する表示します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobPipelineInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineInformation (Nullable&lt;Guid&gt; pipelineId = null, string pipelineName = null, string pipelineUri = null, Nullable&lt;int&gt; numJobsFailed = null, Nullable&lt;int&gt; numJobsCanceled = null, Nullable&lt;int&gt; numJobsSucceeded = null, Nullable&lt;double&gt; auHoursFailed = null, Nullable&lt;double&gt; auHoursCanceled = null, Nullable&lt;double&gt; auHoursSucceeded = null, Nullable&lt;DateTimeOffset&gt; lastSubmitTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; runs = null, System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; recurrences = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; pipelineId, string pipelineName, string pipelineUri, valuetype System.Nullable`1&lt;int32&gt; numJobsFailed, valuetype System.Nullable`1&lt;int32&gt; numJobsCanceled, valuetype System.Nullable`1&lt;int32&gt; numJobsSucceeded, valuetype System.Nullable`1&lt;float64&gt; auHoursFailed, valuetype System.Nullable`1&lt;float64&gt; auHoursCanceled, valuetype System.Nullable`1&lt;float64&gt; auHoursSucceeded, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastSubmitTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; runs, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.Guid&gt;&gt; recurrences) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.#ctor(System.Nullable{System.Guid},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTimeOffset},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation},System.Collections.Generic.IList{System.Nullable{System.Guid}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional pipelineId As Nullable(Of Guid) = null, Optional pipelineName As String = null, Optional pipelineUri As String = null, Optional numJobsFailed As Nullable(Of Integer) = null, Optional numJobsCanceled As Nullable(Of Integer) = null, Optional numJobsSucceeded As Nullable(Of Integer) = null, Optional auHoursFailed As Nullable(Of Double) = null, Optional auHoursCanceled As Nullable(Of Double) = null, Optional auHoursSucceeded As Nullable(Of Double) = null, Optional lastSubmitTime As Nullable(Of DateTimeOffset) = null, Optional runs As IList(Of JobPipelineRunInformation) = null, Optional recurrences As IList(Of Nullable(Of Guid)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation : Nullable&lt;Guid&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation (pipelineId, pipelineName, pipelineUri, numJobsFailed, numJobsCanceled, numJobsSucceeded, auHoursFailed, auHoursCanceled, auHoursSucceeded, lastSubmitTime, runs, recurrences)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipelineId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipelineUri" Type="System.String" />
        <Parameter Name="numJobsFailed" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsCanceled" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="auHoursFailed" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursCanceled" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursSucceeded" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="lastSubmitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="runs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;" />
        <Parameter Name="recurrences" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Guid&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="pipelineId">ジョブの関係パイプライン識別子 (GUID) です。</param>
        <param name="pipelineName">フレンドリなパイプラインの名前、ジョブの関係、一意である必要はありません。</param>
        <param name="pipelineUri">このパイプラインには、元のサービスにパイプライン、uri、一意のリンク</param>
        <param name="numJobsFailed">このパイプライン内で失敗したジョブの数。</param>
        <param name="numJobsCanceled">このパイプラインで取り消されたジョブの数。</param>
        <param name="numJobsSucceeded">このパイプラインに成功したジョブの数。</param>
        <param name="auHoursFailed">失敗したジョブの結果のジョブ実行時間の数。</param>
        <param name="auHoursCanceled">発生したジョブ実行時間の数には、ジョブが取り消されました。</param>
        <param name="auHoursSucceeded">成功したジョブの結果のジョブ実行時間の数。</param>
        <param name="lastSubmitTime">このパイプライン内のジョブが送信された最後の時間。</param>
        <param name="runs">このパイプラインの実行の各を表す繰り返しの識別子のリスト。</param>
        <param name="recurrences">このパイプラインの実行の各を表す繰り返しの識別子のリスト。</param>
        <summary>
            JobPipelineInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursCanceled As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursCanceled : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取り消されたジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursFailed As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursFailed : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            失敗したジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursSucceeded As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursSucceeded : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            成功したジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.LastSubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.LastSubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastSubmitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパイプライン内のジョブが送信された最後の時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsCanceled As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsCanceled : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取り消されたこのパイプラインでは、ジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsFailed As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsFailed : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパイプラインで失敗したジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            成功したこのパイプラインでは、ジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PipelineId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PipelineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PipelineId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの関係パイプライン識別子 (GUID) を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一意である必要はありません、ジョブの関係パイプラインのフレンドリ名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineUri">
      <MemberSignature Language="C#" Value="public string PipelineUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineUri As String" />
      <MemberSignature Language="F#" Value="member this.PipelineUri : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パイプライン uri、一意で、このパイプラインには、元のサービスへのリンクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; Recurrences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.Guid&gt;&gt; Recurrences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Recurrences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recurrences As IList(Of Nullable(Of Guid))" />
      <MemberSignature Language="F#" Value="member this.Recurrences : System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Recurrences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Guid&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパイプラインの各実行を表す繰り返しの識別子の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; Runs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; Runs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Runs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Runs As IList(Of JobPipelineRunInformation)" />
      <MemberSignature Language="F#" Value="member this.Runs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Runs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパイプラインの各実行を表す繰り返しの識別子の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPipelineInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>