<Type Name="ResourceStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics">
  <TypeSignature Language="C#" Value="public class ResourceStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceStatistics" />
  <TypeSignature Language="F#" Value="type ResourceStatistics = class" />
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
            プール内のコンピューティング ノードでリソースの消費量に関連する統計。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.#ctor" />
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
            ResourceStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceStatistics (DateTime startTime, DateTime lastUpdateTime, double avgCPUPercentage, double avgMemoryGiB, double peakMemoryGiB, double avgDiskGiB, double peakDiskGiB, long diskReadIOps, long diskWriteIOps, double diskReadGiB, double diskWriteGiB, double networkReadGiB, double networkWriteGiB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, float64 avgCPUPercentage, float64 avgMemoryGiB, float64 peakMemoryGiB, float64 avgDiskGiB, float64 peakDiskGiB, int64 diskReadIOps, int64 diskWriteIOps, float64 diskReadGiB, float64 diskWriteGiB, float64 networkReadGiB, float64 networkWriteGiB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.#ctor(System.DateTime,System.DateTime,System.Double,System.Double,System.Double,System.Double,System.Double,System.Int64,System.Int64,System.Double,System.Double,System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, lastUpdateTime As DateTime, avgCPUPercentage As Double, avgMemoryGiB As Double, peakMemoryGiB As Double, avgDiskGiB As Double, peakDiskGiB As Double, diskReadIOps As Long, diskWriteIOps As Long, diskReadGiB As Double, diskWriteGiB As Double, networkReadGiB As Double, networkWriteGiB As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics : DateTime * DateTime * double * double * double * double * double * int64 * int64 * double * double * double * double -&gt; Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics (startTime, lastUpdateTime, avgCPUPercentage, avgMemoryGiB, peakMemoryGiB, avgDiskGiB, peakDiskGiB, diskReadIOps, diskWriteIOps, diskReadGiB, diskWriteGiB, networkReadGiB, networkWriteGiB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="avgCPUPercentage" Type="System.Double" />
        <Parameter Name="avgMemoryGiB" Type="System.Double" />
        <Parameter Name="peakMemoryGiB" Type="System.Double" />
        <Parameter Name="avgDiskGiB" Type="System.Double" />
        <Parameter Name="peakDiskGiB" Type="System.Double" />
        <Parameter Name="diskReadIOps" Type="System.Int64" />
        <Parameter Name="diskWriteIOps" Type="System.Int64" />
        <Parameter Name="diskReadGiB" Type="System.Double" />
        <Parameter Name="diskWriteGiB" Type="System.Double" />
        <Parameter Name="networkReadGiB" Type="System.Double" />
        <Parameter Name="networkWriteGiB" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="startTime">統計情報の時間範囲の開始時刻です。</param>
        <param name="lastUpdateTime">これで、統計の最終更新時刻。 すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</param>
        <param name="avgCPUPercentage">プール (ノードあたりの割合) 内のすべてのノードで平均の CPU 使用率。</param>
        <param name="avgMemoryGiB">プール内のすべてのノードで 平均メモリ使用率 GiB で。</param>
        <param name="peakMemoryGiB">ピーク時のメモリ使用量 GiB、プール内のすべてのノード間でします。</param>
        <param name="avgDiskGiB">平均は、プールで GiB 内のすべてのノード間でのディスク領域を使用します。</param>
        <param name="peakDiskGiB">ピーク時では、プールで GiB 内のすべてのノード間でのディスク領域を使用します。</param>
        <param name="diskReadIOps">プール内のすべてのノードでの読み取り操作をディスクの合計数。</param>
        <param name="diskWriteIOps">プール内のすべてのノードで書き込み操作をディスクの合計数。</param>
        <param name="diskReadGiB">プール内のすべてのノードでディスクの GiB 内のデータの総量を読み取ります。</param>
        <param name="diskWriteGiB">プール内のすべてのノードでディスクの GiB 内のデータの総量を書き込みます。</param>
        <param name="networkReadGiB">プール内のすべてのノード間でネットワークの GiB 内のデータの総量を読み取ります。</param>
        <param name="networkWriteGiB">プール内のすべてのノード間でネットワークの GiB 内のデータの総量を書き込みます。</param>
        <summary>
            ResourceStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgCPUPercentage">
      <MemberSignature Language="C#" Value="public double AvgCPUPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgCPUPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgCPUPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgCPUPercentage As Double" />
      <MemberSignature Language="F#" Value="member this.AvgCPUPercentage : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgCPUPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgCPUPercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール (ノードあたりの割合) 内のすべてのノードで、平均 CPU 使用率を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgDiskGiB">
      <MemberSignature Language="C#" Value="public double AvgDiskGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AvgDiskGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgDiskGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内のすべてのノードで、平均の使用済みディスク領域を GiB に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgMemoryGiB">
      <MemberSignature Language="C#" Value="public double AvgMemoryGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 AvgMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property AvgMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.AvgMemoryGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.AvgMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgMemoryGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内のすべてのノードで、平均メモリ使用量を GiB に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadGiB">
      <MemberSignature Language="C#" Value="public double DiskReadGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskReadGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskReadGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または GiB ディスクの読み取りで、プール内のすべてのノード間でデータの合計サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskReadIOps">
      <MemberSignature Language="C#" Value="public long DiskReadIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskReadIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskReadIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはディスクのプール内のすべてのノード間で読み込み操作の合計数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteGiB">
      <MemberSignature Language="C#" Value="public double DiskWriteGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DiskWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.DiskWriteGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskWriteGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または GiB ディスクへの書き込みで、プール内のすべてのノード間でデータの合計サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskWriteIOps">
      <MemberSignature Language="C#" Value="public long DiskWriteIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DiskWriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskWriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.DiskWriteIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.DiskWriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskWriteIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内のすべてのノード間でのディスク書き込み操作の合計数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定する、統計の最終更新時刻。
            すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkReadGiB">
      <MemberSignature Language="C#" Value="public double NetworkReadGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkReadGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkReadGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkReadGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkReadGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkReadGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkReadGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワーク読み取りの GiB で、プール内のすべてのノード間でデータの合計サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWriteGiB">
      <MemberSignature Language="C#" Value="public double NetworkWriteGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 NetworkWriteGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkWriteGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkWriteGiB As Double" />
      <MemberSignature Language="F#" Value="member this.NetworkWriteGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.NetworkWriteGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkWriteGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワークの書き込みの GiB でプール内のすべてのノード間でデータの合計サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakDiskGiB">
      <MemberSignature Language="C#" Value="public double PeakDiskGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakDiskGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakDiskGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakDiskGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakDiskGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakDiskGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="peakDiskGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または GiB でプール内のすべてのノードにわたってピーク時使用ディスク領域を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeakMemoryGiB">
      <MemberSignature Language="C#" Value="public double PeakMemoryGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 PeakMemoryGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakMemoryGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property PeakMemoryGiB As Double" />
      <MemberSignature Language="F#" Value="member this.PeakMemoryGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.PeakMemoryGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="peakMemoryGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または GiB でプール内のすべてのノードにわたってピーク時のメモリ使用量を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または統計の時間範囲の開始時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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