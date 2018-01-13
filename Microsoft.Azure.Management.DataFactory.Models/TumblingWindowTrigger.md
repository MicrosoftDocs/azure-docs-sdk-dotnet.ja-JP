<Type Name="TumblingWindowTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger">
  <TypeSignature Language="C#" Value="public class TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TumblingWindowTrigger extends Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class TumblingWindowTrigger&#xA;Inherits Trigger" />
  <TypeSignature Language="F#" Value="type TumblingWindowTrigger = class&#xA;    inherit Trigger" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Trigger</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            パイプラインをスケジュールするトリガーでは、置かず開始時刻からすべての一定の時間間隔の windows を実行するときし、(開始時刻が過去の場合) もバックフィル シナリオをサポートしています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TumblingWindowTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger (Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, string frequency = null, Nullable&lt;int&gt; interval = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, object delay = null, Nullable&lt;int&gt; maxConcurrency = null, Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, string frequency, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, object delay, valuetype System.Nullable`1&lt;int32&gt; maxConcurrency, class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor(Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Object,System.Nullable{System.Int32},Microsoft.Azure.Management.DataFactory.Models.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * obj * Nullable&lt;int&gt; * Microsoft.Azure.Management.DataFactory.Models.RetryPolicy -&gt; Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger (pipeline, additionalProperties, description, runtimeState, frequency, interval, startTime, endTime, delay, maxConcurrency, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
        <Parameter Name="frequency" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="delay" Type="System.Object" />
        <Parameter Name="maxConcurrency" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Management.DataFactory.Models.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="pipeline">パイプラインを実行を準備ができているウィンドウのトリガーのイベントが発生したときに作成されます。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">トリガーの説明です。</param>
        <param name="runtimeState">トリガーが実行されているかを示します。
            トリガーで開始/停止 Api が呼び出されたときに更新されます。 使用可能な値が含まれます: 'の開始'、'停止'、'Disabled'</param>
        <param name="frequency">時間枠の頻度です。 使用可能な値が含まれます: 'Minute'、'Hour'</param>
        <param name="interval">間隔の時間枠です。 許可されている最小間隔とは、15 分です。</param>
        <param name="startTime">準備ができている windows のイベントが発生するトリガーの期間の開始時刻。
            UTC 時刻だけは現在サポートされています。</param>
        <param name="endTime">準備ができている windows のイベントが発生するトリガーの期間の終了時刻。
            UTC 時刻だけは現在サポートされています。</param>
        <param name="delay">期限のトリガーの待機時間を指定新しい実行をトリガするまでの時間。 Alter ウィンドウの開始と終了時刻にしません。 既定値は 0 です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="maxConcurrency">新しい実行がトリガーされた並列の時間枠 (実行の準備完了) の最大数。</param>
        <param name="retryPolicy">失敗したパイプラインの実行に適用されるポリシーを再試行してください。</param>
        <summary>
            TumblingWindowTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public object Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As Object" />
      <MemberSignature Language="F#" Value="member this.Delay : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.delay")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            期限のトリガーの待機時間を指定を取得または設定前に、新しい実行をトリガーする時間。 Alter ウィンドウの開始と終了時刻にしません。 既定値は 0 です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または準備ができている windows のイベントが発生するトリガーの期間の終了時刻を設定します。 UTC 時刻だけは現在サポートされています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間枠の頻度を設定します。 使用可能な値が含まれます: 'Minute'、'Hour'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間帯の期間を設定します。 許可されている最小間隔とは、15 分です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxConcurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxConcurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.maxConcurrency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または新規の実行がトリガーされるの並列の時間枠 (実行の準備完了) の最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipeline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberSignature Language="VB.NET" Value="Public Property Pipeline As TriggerPipelineReference" />
      <MemberSignature Language="F#" Value="member this.Pipeline : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipeline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成対象の実行は準備ができているウィンドウのトリガーのイベントが発生したときにパイプラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Management.DataFactory.Models.RetryPolicy with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.retryPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または失敗したパイプラインの実行に適用される再試行ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または準備ができている windows のイベントが発生するトリガーの期間の開始時刻を設定します。 UTC 時刻だけは現在サポートされています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tumblingWindowTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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