<Type Name="JobFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter">
  <TypeSignature Language="C#" Value="public class JobFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobFilter" />
  <TypeSignature Language="F#" Value="type JobFilter = class" />
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
            ジョブに使用する OData フィルターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter (string status = null, string jobType = null, Nullable&lt;DateTime&gt; startTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, string jobType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional jobType As String = null, Optional startTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter (status, jobType, startTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status">フィルター処理するジョブの状態を指定します。 たとえば、"Running"、「成功」、「失敗」や「キャンセル」です。
            唯一の 'Equality' 演算子については、このプロパティのサポートします。</param>
        <param name="jobType">フィルター処理するジョブの種類を指定します。 例:"ScheduledBackup"、"ManualBackup"、"RestoreBackup"、"CloneVolume"、"FailoverVolumeContainers"、"CreateLocallyPinnedVolume"、"ModifyVolume"、"InstallUpdates"、"SupportPackageLogs"または"CreateCloudAppliance"です。 このプロパティの唯一の 'Equality' 演算子を使用できます。</param>
        <param name="startTime">フィルター処理するジョブの開始時刻を指定します。  のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。</param>
        <summary>
            JobFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public string JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As String" />
      <MemberSignature Language="F#" Value="member this.JobType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、フィルター処理するジョブの種類を指定します。 例:"ScheduledBackup"、"ManualBackup"、"RestoreBackup"、"CloneVolume"、"FailoverVolumeContainers"、"CreateLocallyPinnedVolume"、"ModifyVolume"、"InstallUpdates"、"SupportPackageLogs"または"CreateCloudAppliance"です。 このプロパティの唯一の 'Equality' 演算子を使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、フィルター処理するジョブの開始時刻を指定します。
            のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、フィルター処理するジョブの状態を指定します。 たとえば、"Running"、「成功」、「失敗」や「キャンセル」です。 唯一の 'Equality' 演算子については、このプロパティのサポートします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>