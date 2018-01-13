<Type Name="JobInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation">
  <TypeSignature Language="C#" Value="public class JobInformation : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInformation extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInformation&#xA;Inherits JobInformationBasic" />
  <TypeSignature Language="F#" Value="type JobInformation = class&#xA;    inherit JobInformationBasic" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            拡張の Data Lake Analytics ジョブの特定のジョブを取得するときに返される情報のプロパティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation (string name, Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, Nullable&lt;Guid&gt; jobId = null, string submitter = null, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, Nullable&lt;DateTimeOffset&gt; submitTime = null, Nullable&lt;DateTimeOffset&gt; startTime = null, Nullable&lt;DateTimeOffset&gt; endTime = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result = null, string logFolder = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; jobId, string submitter, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; submitTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result, string logFolder, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties,System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult},System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As JobType, properties As JobProperties, Optional jobId As Nullable(Of Guid) = null, Optional submitter As String = null, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional submitTime As Nullable(Of DateTimeOffset) = null, Optional startTime As Nullable(Of DateTimeOffset) = null, Optional endTime As Nullable(Of DateTimeOffset) = null, Optional state As Nullable(Of JobState) = null, Optional result As Nullable(Of JobResult) = null, Optional logFolder As String = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null, Optional errorMessage As IList(Of JobErrorDetails) = null, Optional stateAuditRecords As IList(Of JobStateAuditRecord) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation : string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties * Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation (name, type, properties, jobId, submitter, degreeOfParallelism, priority, submitTime, startTime, endTime, state, result, logFolder, logFilePatterns, related, errorMessage, stateAuditRecords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
        <Parameter Name="jobId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="submitter" Type="System.String" />
        <Parameter Name="degreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="submitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt;" />
        <Parameter Name="logFolder" Type="System.String" />
        <Parameter Name="logFilePatterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="related" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
        <Parameter Name="errorMessage" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" />
        <Parameter Name="stateAuditRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" />
      </Parameters>
      <Docs>
        <param name="name">ジョブのフレンドリ名。</param>
        <param name="type">(Hive または USql) は、現在のジョブのジョブの種類。
            使用可能な値が含まれます: 'USql'、'ハイブ'</param>
        <param name="properties">ジョブの特定プロパティです。</param>
        <param name="jobId">ジョブの一意の識別子 (GUID)。</param>
        <param name="submitter">ユーザーまたはジョブを送信するアカウント。</param>
        <param name="degreeOfParallelism">このジョブに対して使用される並列処理の次数。 場合 1 を 0 未満の値の設定は既定値は 0 より大きくにあります。</param>
        <param name="priority">現在のジョブの優先度の値。
            数値が小さいほど優先順位が高いがあります。 、既定では、ジョブは、1000 の優先順位を持ちます。 これは、0 より大きくなければなりません。</param>
        <param name="submitTime">ジョブがサービスに送信された時刻。</param>
        <param name="startTime">ジョブの開始時刻です。</param>
        <param name="endTime">ジョブの完了時間。</param>
        <param name="state">ジョブの状態。 ジョブが終了状態になった場合、詳細結果とエラー メッセージを参照してください。 使用可能な値が含まれます: '許可'、'コンパイル'、'終了'、'New'、'Queued'、'実行中、'スケジューリング'、' 開始'、'一時停止中'、'WaitingForCapacity'</param>
        <param name="result">ジョブの実行や、現在実行中のジョブの結果の結果。 使用可能な値が含まれます 'None'、'成功'、'キャンセル'、'失敗'。</param>
        <param name="logFolder">次の形式で使用するログ フォルダーのパス: 含む://&lt;accountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/ です。</param>
        <param name="logFilePatterns">logFolder 内を検索するログ ファイル名パターンの一覧。 '*' は許可されている唯一の一致する文字。形式の例: jobExecution*.log または*mylog*.txt</param>
        <param name="related">定期的なジョブ関係情報のプロパティです。</param>
        <param name="errorMessage">ジョブが失敗した場合、ジョブのエラー メッセージの詳細。</param>
        <param name="stateAuditRecords">ジョブの状態は、さまざまな操作でこのジョブで実行されたときにサイズを示すレコードを監査します。</param>
        <summary>
            JobInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As IList(Of JobErrorDetails)" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラー メッセージの詳細を取得、ジョブ、ジョブが失敗した場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As JobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブを特定のプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateAuditRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateAuditRecords As IList(Of JobStateAuditRecord)" />
      <MemberSignature Language="F#" Value="member this.StateAuditRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateAuditRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブのジョブのさまざまな操作が実行されたときにサイズを示す状態監査レコードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="jobInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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