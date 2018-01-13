<Type Name="JobErrorDetails" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails">
  <TypeSignature Language="C#" Value="public class JobErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class JobErrorDetails" />
  <TypeSignature Language="F#" Value="type JobErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Analytics ジョブのエラーの詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobErrorDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails (string description = null, string details = null, Nullable&lt;int&gt; endOffset = null, string errorId = null, string filePath = null, string helpLink = null, string internalDiagnostics = null, Nullable&lt;int&gt; lineNumber = null, string message = null, string resolution = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity = null, string source = null, Nullable&lt;int&gt; startOffset = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string description, string details, valuetype System.Nullable`1&lt;int32&gt; endOffset, string errorId, string filePath, string helpLink, string internalDiagnostics, valuetype System.Nullable`1&lt;int32&gt; lineNumber, string message, string resolution, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity, string source, valuetype System.Nullable`1&lt;int32&gt; startOffset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.#ctor(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError,System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional description As String = null, Optional details As String = null, Optional endOffset As Nullable(Of Integer) = null, Optional errorId As String = null, Optional filePath As String = null, Optional helpLink As String = null, Optional internalDiagnostics As String = null, Optional lineNumber As Nullable(Of Integer) = null, Optional message As String = null, Optional resolution As String = null, Optional innerError As JobInnerError = null, Optional severity As Nullable(Of SeverityTypes) = null, Optional source As String = null, Optional startOffset As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails : string * string * Nullable&lt;int&gt; * string * string * string * string * Nullable&lt;int&gt; * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails (description, details, endOffset, errorId, filePath, helpLink, internalDiagnostics, lineNumber, message, resolution, innerError, severity, source, startOffset)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="endOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="helpLink" Type="System.String" />
        <Parameter Name="internalDiagnostics" Type="System.String" />
        <Parameter Name="lineNumber" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="innerError" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="startOffset" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="description">エラー メッセージの説明</param>
        <param name="details">エラー メッセージの詳細。</param>
        <param name="endOffset">エラーが見つかりましたが、ジョブの終了オフセット。</param>
        <param name="errorId">ジョブで発生したエラーの種類の特定の識別子。</param>
        <param name="filePath">存在する場合、補足的なエラー ファイルへのパス。</param>
        <param name="helpLink">MSDN または Azure へのリンクは、存在する場合、この種類のエラーのヘルプします。</param>
        <param name="internalDiagnostics">ジョブ エラーの詳細を要求するユーザーを取得するための十分なアクセス許可がある場合は、内部診断スタック トレース、それ以外の場合、空になります。</param>
        <param name="lineNumber">エラーが発生したジョブの特定の行番号。</param>
        <param name="message">障害のユーザー フレンドリ エラー メッセージ。</param>
        <param name="resolution">存在する場合、失敗の推奨される解決方法です。</param>
        <param name="innerError">この特定のジョブ エラー メッセージ、存在する場合の内部エラーです。</param>
        <param name="severity">エラーの重大度レベル。 使用可能な値が含まれます: 'Warning'、'Error'、'情報'、'SevereWarning'、'非推奨'、'UserWarning'</param>
        <param name="source">エラーの最終的なソース (通常、システムまたはユーザー)。</param>
        <param name="startOffset">エラーが見つかりましたジョブの開始オフセット</param>
        <summary>
            JobErrorDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラー メッセージの説明を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラー メッセージの詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EndOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EndOffset : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.EndOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーが見つかりましたジョブの終了オフセットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブで発生したエラーの種類の特定の識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合は、任意の補足的なエラー ファイルへのパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HelpLink">
      <MemberSignature Language="C#" Value="public string HelpLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HelpLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.HelpLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HelpLink As String" />
      <MemberSignature Language="F#" Value="member this.HelpLink : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.HelpLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="helpLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合は、この種のエラー、MSDN または Azure のヘルプへのリンクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InnerError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerError As JobInnerError" />
      <MemberSignature Language="F#" Value="member this.InnerError : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InnerError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innerError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合は、この特定のジョブのエラー メッセージの内部エラーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDiagnostics">
      <MemberSignature Language="C#" Value="public string InternalDiagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InternalDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDiagnostics As String" />
      <MemberSignature Language="F#" Value="member this.InternalDiagnostics : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.InternalDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブ エラーの詳細を取得するための十分なアクセス許可を要求するユーザー、それ以外の場合に空にする場合は、内部診断スタック トレースを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LineNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LineNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LineNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.LineNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LineNumber As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LineNumber : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.LineNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lineNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーが発生したジョブ内の特定の行番号を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーのユーザー フレンドリ エラー メッセージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合、エラーが発生する、推奨される解像度を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As Nullable(Of SeverityTypes)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーの重大度レベルを取得します。 使用可能な値が含まれます: 'Warning'、'Error'、'情報'、'SevereWarning'、'非推奨'、'UserWarning'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーの最終的なソースを取得 (通常、システムまたはユーザー)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StartOffset : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーが見つかりましたジョブの開始オフセットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>