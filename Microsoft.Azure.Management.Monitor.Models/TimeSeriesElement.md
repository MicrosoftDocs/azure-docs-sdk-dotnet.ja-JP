<Type Name="TimeSeriesElement" FullName="Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement">
  <TypeSignature Language="C#" Value="public class TimeSeriesElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TimeSeriesElement extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TimeSeriesElement" />
  <TypeSignature Language="F#" Value="type TimeSeriesElement = class" />
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
            タイム シリーズには、種類があります。 識別子の値は常に TimeSeries ここでです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSeriesElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.#ctor" />
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
            TimeSeriesElement クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TimeSeriesElement (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; metadatavalues = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; data = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; metadatavalues, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.MetricValue})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional metadatavalues As IList(Of MetadataValue) = null, Optional data As IList(Of MetricValue) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement" Usage="new Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement (metadatavalues, data)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadatavalues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="data" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt;" />
      </Parameters>
      <Docs>
        <param name="metadatavalues">$filter を呼び出しで指定されたかどうか、メタデータ値が返されます。</param>
        <param name="data">メトリックの値を表すデータ点の配列。  データの結果型が指定されている場合のみ返されます。</param>
        <summary>
            TimeSeriesElement クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As IList(Of MetricValue)" />
      <MemberSignature Language="F#" Value="member this.Data : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメトリックの値を表すデータ点の配列を設定します。  データの結果型が指定されている場合のみ返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadatavalues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; Metadatavalues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; Metadatavalues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.Metadatavalues" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadatavalues As IList(Of MetadataValue)" />
      <MemberSignature Language="F#" Value="member this.Metadatavalues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement.Metadatavalues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadatavalues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または $filter が呼び出しで指定されたかどうかに値が返されるメタデータを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>