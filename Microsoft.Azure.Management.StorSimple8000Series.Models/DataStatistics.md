<Type Name="DataStatistics" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics">
  <TypeSignature Language="C#" Value="public class DataStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class DataStatistics" />
  <TypeSignature Language="F#" Value="type DataStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            追加の詳細データに関連するジョブの関連する統計。
            現在適用可能なバックアップ、複製、復元ジョブに対してのみです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataStatistics (Nullable&lt;long&gt; totalData = null, Nullable&lt;long&gt; processedData = null, Nullable&lt;long&gt; cloudData = null, Nullable&lt;long&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; totalData, valuetype System.Nullable`1&lt;int64&gt; processedData, valuetype System.Nullable`1&lt;int64&gt; cloudData, valuetype System.Nullable`1&lt;int64&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional totalData As Nullable(Of Long) = null, Optional processedData As Nullable(Of Long) = null, Optional cloudData As Nullable(Of Long) = null, Optional throughput As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics (totalData, processedData, cloudData, throughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="totalData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="processedData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cloudData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="totalData">ジョブの一部として処理するデータの合計バイト数。</param>
        <param name="processedData">ここでは、まで、ジョブの一部として処理されるデータのバイト数。</param>
        <param name="cloudData">ジョブの一部として、クラウドに書き込まれたデータのバイト数。</param>
        <param name="throughput">ジョブの一部として、データ processed(bytes/sec) の平均スループット。</param>
        <summary>
            DataStatistics クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CloudData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CloudData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.CloudData" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CloudData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.CloudData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの一部として、クラウドに書き込まれたデータのバイト数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessedData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProcessedData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProcessedData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.ProcessedData" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessedData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProcessedData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.ProcessedData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processedData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの一部として、これまで処理したデータのバイト数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Throughput">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Throughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Throughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.Throughput" />
      <MemberSignature Language="VB.NET" Value="Public Property Throughput As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Throughput : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.Throughput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="throughput")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの一部としてデータ processed(bytes/sec) の平均スループットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.TotalData" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.TotalData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの一部として処理するデータの合計バイト数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>