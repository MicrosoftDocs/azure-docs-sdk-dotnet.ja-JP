<Type Name="MetricTrigger" FullName="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger">
  <TypeSignature Language="C#" Value="public class MetricTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricTrigger" />
  <TypeSignature Language="F#" Value="type MetricTrigger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            スケーリング処理で生成されるトリガー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MetricTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger (string metricName, string metricResourceUri, TimeSpan timeGrain, Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, TimeSpan timeWindow, Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, double threshold);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metricName, string metricResourceUri, valuetype System.TimeSpan timeGrain, valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, valuetype System.TimeSpan timeWindow, valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, float64 threshold) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor(System.String,System.String,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType,Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metricName As String, metricResourceUri As String, timeGrain As TimeSpan, statistic As MetricStatisticType, timeWindow As TimeSpan, timeAggregation As TimeAggregationType, operatorProperty As ComparisonOperationType, threshold As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger : string * string * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType * Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType * double -&gt; Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger (metricName, metricResourceUri, timeGrain, statistic, timeWindow, timeAggregation, operatorProperty, threshold)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metricName" Type="System.String" />
        <Parameter Name="metricResourceUri" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.TimeSpan" />
        <Parameter Name="statistic" Type="Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType" />
        <Parameter Name="timeWindow" Type="System.TimeSpan" />
        <Parameter Name="timeAggregation" Type="Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType" />
        <Parameter Name="operatorProperty" Type="Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType" />
        <Parameter Name="threshold" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="metricName">ルールの監視対象を定義するメトリックの名前。</param>
        <param name="metricResourceUri">ルールのリソースのリソース識別子を監視します。</param>
        <param name="timeGrain">ルールのメトリックの粒度を監視します。 返す必要がある定義済みの値のいずれかのメトリックのメトリック定義からです。 12 時間から 1 分間でなければなりません。</param>
        <param name="statistic">メトリックの統計の種類。 複数のインスタンスからメトリックを結合方法です。 使用可能な値が含まれます: 'Average'、'Min'、'Max'、'Sum'</param>
        <param name="timeWindow">データの収集先のインスタンスで時間の範囲です。 この値は、リソースのリソースは異なる場合、メトリックのコレクションでの遅延より大きくなければなりません。 12 時間から 5 分間でなければなりません。</param>
        <param name="timeAggregation">時間の集計の種類。 収集されたデータの経時的な結合方法。 既定値は Average です。 使用可能な値が含まれます: '平均'、'最小'、'最大'、'Total'、'Count'</param>
        <param name="operatorProperty">メトリック データとしきい値の比較に使用される演算子です。 使用可能な値が含まれます 'Equals'、'NotEquals'、'GreaterThan'、'GreaterThanOrEqual'、"LessThan"、"LessThanOrEqual"。</param>
        <param name="threshold">スケール操作をトリガーするメトリックのしきい値。</param>
        <summary>
            MetricTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricName">
      <MemberSignature Language="C#" Value="public string MetricName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricName As String" />
      <MemberSignature Language="F#" Value="member this.MetricName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはルールの監視対象を定義するメトリックの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricResourceUri">
      <MemberSignature Language="C#" Value="public string MetricResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.MetricResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、リソース、ルールのリソース識別子を監視します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As ComparisonOperationType" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメトリック データとしきい値の比較に使用される演算子を設定します。 使用可能な値が含まれます 'Equals'、'NotEquals'、'GreaterThan'、'GreaterThanOrEqual'、"LessThan"、"LessThanOrEqual"。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberSignature Language="VB.NET" Value="Public Property Statistic As MetricStatisticType" />
      <MemberSignature Language="F#" Value="member this.Statistic : Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statistic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメトリックの統計の種類を設定します。 複数のインスタンスからメトリックを結合方法です。 使用可能な値が含まれます: 'Average'、'Min'、'Max'、'Sum'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threshold">
      <MemberSignature Language="C#" Value="public double Threshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Threshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberSignature Language="VB.NET" Value="Public Property Threshold As Double" />
      <MemberSignature Language="F#" Value="member this.Threshold : double with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="threshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケール アクションをトリガーするメトリックのしきい値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeAggregation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeAggregation As TimeAggregationType" />
      <MemberSignature Language="F#" Value="member this.TimeAggregation : Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の集計の種類を設定します。 収集されたデータの経時的な結合方法。 既定値は Average です。
            使用可能な値が含まれます: '平均'、'最小'、'最大'、'Total'、'Count'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public TimeSpan TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定ルールのメトリックの粒度を監視します。 返す必要がある定義済みの値のいずれかのメトリックのメトリック定義からです。 12 時間から 1 分間でなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan TimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeWindow : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはインスタンス データが収集される時間の範囲を設定します。
            この値は、リソースのリソースは異なる場合、メトリックのコレクションでの遅延より大きくなければなりません。 12 時間から 5 分間でなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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