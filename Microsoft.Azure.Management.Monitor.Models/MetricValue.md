<Type Name="MetricValue" FullName="Microsoft.Azure.Management.Monitor.Models.MetricValue">
  <TypeSignature Language="C#" Value="public class MetricValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.MetricValue" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricValue" />
  <TypeSignature Language="F#" Value="type MetricValue = class" />
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
            メトリックの値を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricValue.#ctor" />
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
            MetricValue クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue (DateTime timeStamp, Nullable&lt;double&gt; average = null, Nullable&lt;double&gt; minimum = null, Nullable&lt;double&gt; maximum = null, Nullable&lt;double&gt; total = null, Nullable&lt;long&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime timeStamp, valuetype System.Nullable`1&lt;float64&gt; average, valuetype System.Nullable`1&lt;float64&gt; minimum, valuetype System.Nullable`1&lt;float64&gt; maximum, valuetype System.Nullable`1&lt;float64&gt; total, valuetype System.Nullable`1&lt;int64&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricValue.#ctor(System.DateTime,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timeStamp As DateTime, Optional average As Nullable(Of Double) = null, Optional minimum As Nullable(Of Double) = null, Optional maximum As Nullable(Of Double) = null, Optional total As Nullable(Of Double) = null, Optional count As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.MetricValue : DateTime * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.MetricValue" Usage="new Microsoft.Azure.Management.Monitor.Models.MetricValue (timeStamp, average, minimum, maximum, total, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeStamp" Type="System.DateTime" />
        <Parameter Name="average" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="total" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="timeStamp">ISO 8601 形式でメトリックの値のタイムスタンプ。</param>
        <param name="average">時間範囲の平均値です。</param>
        <param name="minimum">時間範囲の最小値です。</param>
        <param name="maximum">時間範囲の最大値。</param>
        <param name="total">すべての時間範囲の値の合計。</param>
        <param name="count">時間の範囲内のサンプルの数。 平均値に寄与する値の数を決定するために使用します。</param>
        <summary>
            MetricValue クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Average { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.Average" />
      <MemberSignature Language="VB.NET" Value="Public Property Average As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Average : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="average")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の範囲内の平均値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の範囲内のサンプルの数を設定します。 平均値に寄与する値の数を決定するために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Maximum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public Property Maximum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の範囲内の最大値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Minimum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public Property Minimum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の範囲で最低の値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public DateTime TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ISO 8601 形式でメトリックの値のタイムスタンプを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Total { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.MetricValue.Total" />
      <MemberSignature Language="VB.NET" Value="Public Property Total As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Total : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.MetricValue.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="total")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の範囲内のすべての値の合計を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.MetricValue.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricValue.Validate " />
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