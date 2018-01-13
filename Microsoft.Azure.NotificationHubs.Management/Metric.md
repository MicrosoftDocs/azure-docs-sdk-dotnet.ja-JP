<Type Name="Metric" FullName="Microsoft.Azure.NotificationHubs.Management.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Service Bus の状態を監視するために使用するメトリックを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.Metric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Management.Metric" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.Metric.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.Metric.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの表示名を設定します。</summary>
        <value>メトリックの表示名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの名前を設定します。</summary>
        <value>メトリックの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregation">
      <MemberSignature Language="C#" Value="public string PrimaryAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.Metric.PrimaryAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregation : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.Metric.PrimaryAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのメトリックの集計をプライマリを設定します。</summary>
        <value>このメトリックの集計をプライマリです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rollups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricRollup&gt; Rollups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.NotificationHubs.Management.MetricRollup&gt; Rollups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.Metric.Rollups" />
      <MemberSignature Language="VB.NET" Value="Public Property Rollups As ICollection(Of MetricRollup)" />
      <MemberSignature Language="F#" Value="member this.Rollups : System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricRollup&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.Metric.Rollups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricRollup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックのロールアップのコレクションを設定します。</summary>
        <value>メトリック ロールアップのコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメトリックの単位を設定します。</summary>
        <value>メトリックの単位です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>