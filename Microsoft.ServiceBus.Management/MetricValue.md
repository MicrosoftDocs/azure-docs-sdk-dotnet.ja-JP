<Type Name="MetricValue" FullName="Microsoft.ServiceBus.Management.MetricValue">
  <TypeSignature Language="C#" Value="public class MetricValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.MetricValue" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricValue" />
  <TypeSignature Language="F#" Value="type MetricValue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>サービス バスに関連付けられているメトリックの値を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.MetricValue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public float Average { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float32 Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricValue.Average" />
      <MemberSignature Language="VB.NET" Value="Public Property Average As Single" />
      <MemberSignature Language="F#" Value="member this.Average : single with get, set" Usage="Microsoft.ServiceBus.Management.MetricValue.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Single</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの平均値を設定します。</summary>
        <value>メトリックの平均値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public long Max { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricValue.Max" />
      <MemberSignature Language="VB.NET" Value="Public Property Max As Long" />
      <MemberSignature Language="F#" Value="member this.Max : int64 with get, set" Usage="Microsoft.ServiceBus.Management.MetricValue.Max" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの最大値を設定します。</summary>
        <value>メトリックの最大値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public long Min { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricValue.Min" />
      <MemberSignature Language="VB.NET" Value="Public Property Min As Long" />
      <MemberSignature Language="F#" Value="member this.Min : int64 with get, set" Usage="Microsoft.ServiceBus.Management.MetricValue.Min" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの最小値を設定します。</summary>
        <value>メトリックの最小値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricValue.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime with get, set" Usage="Microsoft.ServiceBus.Management.MetricValue.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの値に関連付けられたタイムスタンプを設定します。</summary>
        <value>メトリックの値に関連付けられているタイムスタンプ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public long Total { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.MetricValue.Total" />
      <MemberSignature Language="VB.NET" Value="Public Property Total As Long" />
      <MemberSignature Language="F#" Value="member this.Total : int64 with get, set" Usage="Microsoft.ServiceBus.Management.MetricValue.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または合計のメトリックの値を設定します。</summary>
        <value>合計のメトリックの値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>