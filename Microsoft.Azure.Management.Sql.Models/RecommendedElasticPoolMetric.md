<Type Name="RecommendedElasticPoolMetric" FullName="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric">
  <TypeSignature Language="C#" Value="public class RecommendedElasticPoolMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedElasticPoolMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedElasticPoolMetric" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            表すには、弾力性プールのメトリックがお勧めします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RecommendedElasticPoolMetric クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolMetric (Nullable&lt;DateTime&gt; dateTime = null, Nullable&lt;double&gt; dtu = null, Nullable&lt;double&gt; sizeGB = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; dateTime, valuetype System.Nullable`1&lt;float64&gt; dtu, valuetype System.Nullable`1&lt;float64&gt; sizeGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dateTime As Nullable(Of DateTime) = null, Optional dtu As Nullable(Of Double) = null, Optional sizeGB As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric : Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric" Usage="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric (dateTime, dtu, sizeGB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="sizeGB" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="dateTime">メトリック (ISO8601 形式) の時刻。</param>
        <param name="dtu">取得または Dtu (データベース トランザクション ユニット数) を設定します。 Https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/を参照してください。</param>
        <param name="sizeGB">取得またはギガバイト単位でサイズを設定します。</param>
        <summary>
            RecommendedElasticPoolMetric クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.DateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property DateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DateTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.DateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメトリック (ISO8601 形式) の時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Dtu (データベース トランザクション ユニット数) を設定します。 Https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/を参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; SizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; SizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.SizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeGB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.SizeGB : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.SizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはギガバイト単位でサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>