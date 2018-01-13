<Type Name="Alert" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert">
  <TypeSignature Language="C#" Value="public class Alert : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Alert extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" />
  <TypeSignature Language="VB.NET" Value="Public Class Alert&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Alert = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            警告。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            アラートのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert (string title, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, DateTime appearedAtTime, DateTime appearedAtSourceTime, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; clearedAtTime = null, Nullable&lt;DateTime&gt; clearedAtSourceTime = null, string recommendation = null, string resolutionReason = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails = null, System.Collections.Generic.IDictionary&lt;string,string&gt; detailedInformation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string title, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, valuetype System.DateTime appearedAtTime, valuetype System.DateTime appearedAtSourceTime, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtSourceTime, string recommendation, string resolutionReason, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; detailedInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope,System.String,System.DateTime,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (title As String, scope As AlertScope, alertType As String, appearedAtTime As DateTime, appearedAtSourceTime As DateTime, source As AlertSource, severity As AlertSeverity, status As AlertStatus, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional clearedAtTime As Nullable(Of DateTime) = null, Optional clearedAtSourceTime As Nullable(Of DateTime) = null, Optional recommendation As String = null, Optional resolutionReason As String = null, Optional errorDetails As AlertErrorDetails = null, Optional detailedInformation As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope * string * DateTime * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert (title, scope, alertType, appearedAtTime, appearedAtSourceTime, source, severity, status, id, name, type, kind, clearedAtTime, clearedAtSourceTime, recommendation, resolutionReason, errorDetails, detailedInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="scope" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope" />
        <Parameter Name="alertType" Type="System.String" />
        <Parameter Name="appearedAtTime" Type="System.DateTime" />
        <Parameter Name="appearedAtSourceTime" Type="System.DateTime" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource" />
        <Parameter Name="severity" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="clearedAtTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="clearedAtSourceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recommendation" Type="System.String" />
        <Parameter Name="resolutionReason" Type="System.String" />
        <Parameter Name="errorDetails" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails" />
        <Parameter Name="detailedInformation" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="title">警告のタイトル</param>
        <param name="scope">アラートのスコープです。 使用可能な値が含まれます: 'Resource'、'デバイス'</param>
        <param name="alertType">アラートの種類</param>
        <param name="appearedAtTime">アラートが発生した UTC 時刻</param>
        <param name="appearedAtSourceTime">アラートが発生した、元の時刻</param>
        <param name="source">アラートが発生したソース</param>
        <param name="severity">アラートの重大度。 使用可能な値が含まれます: '情報'、'警告'、'重大'</param>
        <param name="status">警告の現在の状態。 使用可能な値が含まれます: 'Active'、'オフ'</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="clearedAtTime">UTC 時刻に警告が消去されました</param>
        <param name="clearedAtSourceTime">元の時刻、警告が消去されました</param>
        <param name="recommendation">アラートの発生した問題の推奨される操作</param>
        <param name="resolutionReason">アラートの解決理由</param>
        <param name="errorDetails">アラートが発生したエラーの詳細</param>
        <param name="detailedInformation">アラートの詳細について</param>
        <summary>
            アラートのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertType">
      <MemberSignature Language="C#" Value="public string AlertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AlertType As String" />
      <MemberSignature Language="F#" Value="member this.AlertType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アラートの種類
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtSourceTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtSourceTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtSourceTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアラートが発生した、元の時刻の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアラートが発生した UTC 時刻の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtSourceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtSourceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtSourceTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、元の時刻、警告が消去されました
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の UTC 時刻に警告が消去されました
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; DetailedInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; DetailedInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedInformation As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.DetailedInformation : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedInformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アラートに関する詳細
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As AlertErrorDetails" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のアラートが発生したエラーの詳細
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendation">
      <MemberSignature Language="C#" Value="public string Recommendation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Recommendation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendation As String" />
      <MemberSignature Language="F#" Value="member this.Recommendation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アラートの発生した問題の推奨される操作
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolutionReason">
      <MemberSignature Language="C#" Value="public string ResolutionReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResolutionReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolutionReason As String" />
      <MemberSignature Language="F#" Value="member this.ResolutionReason : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resolutionReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、アラートの解決理由
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As AlertScope" />
      <MemberSignature Language="F#" Value="member this.Scope : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアラートのスコープを設定します。 使用可能な値が含まれます: 'Resource'、'デバイス'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As AlertSeverity" />
      <MemberSignature Language="F#" Value="member this.Severity : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアラートの重要度を設定します。 使用可能な値が含まれます: '情報'、'警告'、'重大'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As AlertSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アラートが発生したソース取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As AlertStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または警告の現在の状態を設定します。 使用可能な値が含まれます: 'Active'、'オフ'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または警告のタイトルを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="alert.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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