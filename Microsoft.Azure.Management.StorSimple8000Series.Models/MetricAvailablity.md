<Type Name="MetricAvailablity" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity">
  <TypeSignature Language="C#" Value="public class MetricAvailablity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailablity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailablity" />
  <TypeSignature Language="F#" Value="type MetricAvailablity = class" />
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
            メトリックの可用性。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailablity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MetricAvailablity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailablity (string timeGrain = null, string retention = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeGrain, string retention) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As String = null, Optional retention As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity : string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity (timeGrain, retention)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="retention" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeGrain">メトリックの集計間隔です。</param>
        <param name="retention">指定した timegrain でメトリックの保有期間。</param>
        <summary>
            MetricAvailablity クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定した timegrain でメトリックの保有期間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメトリックの集計の間隔を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>