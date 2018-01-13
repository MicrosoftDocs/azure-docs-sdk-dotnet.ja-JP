<Type Name="JobRecurrenceInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation">
  <TypeSignature Language="C#" Value="public class JobRecurrenceInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobRecurrenceInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobRecurrenceInformation" />
  <TypeSignature Language="F#" Value="type JobRecurrenceInformation = class" />
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
            特定の繰り返しの定期的なジョブの情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRecurrenceInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobRecurrenceInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRecurrenceInformation (Nullable&lt;Guid&gt; recurrenceId = null, string recurrenceName = null, Nullable&lt;int&gt; numJobsFailed = null, Nullable&lt;int&gt; numJobsCanceled = null, Nullable&lt;int&gt; numJobsSucceeded = null, Nullable&lt;double&gt; auHoursFailed = null, Nullable&lt;double&gt; auHoursCanceled = null, Nullable&lt;double&gt; auHoursSucceeded = null, Nullable&lt;DateTimeOffset&gt; lastSubmitTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; recurrenceId, string recurrenceName, valuetype System.Nullable`1&lt;int32&gt; numJobsFailed, valuetype System.Nullable`1&lt;int32&gt; numJobsCanceled, valuetype System.Nullable`1&lt;int32&gt; numJobsSucceeded, valuetype System.Nullable`1&lt;float64&gt; auHoursFailed, valuetype System.Nullable`1&lt;float64&gt; auHoursCanceled, valuetype System.Nullable`1&lt;float64&gt; auHoursSucceeded, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastSubmitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.#ctor(System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recurrenceId As Nullable(Of Guid) = null, Optional recurrenceName As String = null, Optional numJobsFailed As Nullable(Of Integer) = null, Optional numJobsCanceled As Nullable(Of Integer) = null, Optional numJobsSucceeded As Nullable(Of Integer) = null, Optional auHoursFailed As Nullable(Of Double) = null, Optional auHoursCanceled As Nullable(Of Double) = null, Optional auHoursSucceeded As Nullable(Of Double) = null, Optional lastSubmitTime As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation : Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation (recurrenceId, recurrenceName, numJobsFailed, numJobsCanceled, numJobsSucceeded, auHoursFailed, auHoursCanceled, auHoursSucceeded, lastSubmitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="recurrenceName" Type="System.String" />
        <Parameter Name="numJobsFailed" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsCanceled" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="auHoursFailed" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursCanceled" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursSucceeded" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="lastSubmitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="recurrenceId">定期的な識別子 (GUID)、イテレーションに関係なく、アクティビティ/スクリプトごとに一意です。 これは、同じジョブの別の出現を一緒にリンクするものです。</param>
        <param name="recurrenceName">定期的な名前では、ジョブ間の相関関係のユーザー フレンドリ名です。</param>
        <param name="numJobsFailed">このパターンの失敗したジョブの数。</param>
        <param name="numJobsCanceled">このパターンの取り消されたジョブの数。</param>
        <param name="numJobsSucceeded">このパターンの成功したジョブの数。</param>
        <param name="auHoursFailed">失敗したジョブの結果のジョブ実行時間の数。</param>
        <param name="auHoursCanceled">発生したジョブ実行時間の数には、ジョブが取り消されました。</param>
        <param name="auHoursSucceeded">成功したジョブの結果のジョブ実行時間の数。</param>
        <param name="lastSubmitTime">このパターンのジョブが送信された最後の時間。</param>
        <summary>
            JobRecurrenceInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursCanceled As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursCanceled : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取り消されたジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursFailed As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursFailed : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            失敗したジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursSucceeded As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursSucceeded : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            成功したジョブの結果のジョブ実行時間の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.LastSubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.LastSubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastSubmitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパターンのジョブが送信された最終時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsCanceled As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsCanceled : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取り消されたこのパターンのジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsFailed As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsFailed : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            失敗したこのパターンのジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このパターンが成功したことのジョブの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RecurrenceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RecurrenceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecurrenceId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            反復処理に関係なく、アクティビティ/スクリプトごとに一意な定期的な識別子 (GUID) を取得します。 これは、同じジョブの別の出現を一緒にリンクするものです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceName">
      <MemberSignature Language="C#" Value="public string RecurrenceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecurrenceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecurrenceName As String" />
      <MemberSignature Language="F#" Value="member this.RecurrenceName : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            定期的なアイテム名、ジョブ間の相関関係のユーザー フレンドリ名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>