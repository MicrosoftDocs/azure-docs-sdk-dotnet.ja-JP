<Type Name="AzureReachabilityReportLatencyInfo" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportLatencyInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportLatencyInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportLatencyInfo" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportLatencyInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タイム シリーズの待機時間について説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportLatencyInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureReachabilityReportLatencyInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportLatencyInfo (Nullable&lt;DateTime&gt; timeStamp = null, Nullable&lt;int&gt; score = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeStamp, valuetype System.Nullable`1&lt;int32&gt; score) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeStamp As Nullable(Of DateTime) = null, Optional score As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo : Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo (timeStamp, score)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="score" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="timeStamp">時刻のタイムスタンプ。</param>
        <param name="score">高速な接続を示す 1 から 100、高い値の間の相対的な待機時間スコアです。</param>
        <summary>
            AzureReachabilityReportLatencyInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Score">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Score { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Score" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.Score" />
      <MemberSignature Language="VB.NET" Value="Public Property Score As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Score : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.Score" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="score")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 1 ~ 100 の高い値を使用して、高速な接続を示す、相対的な待機時間のスコアを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタイムスタンプを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureReachabilityReportLatencyInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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