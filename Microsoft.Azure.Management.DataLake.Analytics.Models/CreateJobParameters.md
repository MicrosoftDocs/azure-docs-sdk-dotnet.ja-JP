<Type Name="CreateJobParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters">
  <TypeSignature Language="C#" Value="public class CreateJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreateJobParameters extends Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CreateJobParameters&#xA;Inherits BaseJobParameters" />
  <TypeSignature Language="F#" Value="type CreateJobParameters = class&#xA;    inherit BaseJobParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            新しい Data Lake Analytics ジョブの送信に使用されるパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CreateJobParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateJobParameters (Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.#ctor(Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As JobType, properties As CreateJobProperties, name As String, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters (type, properties, name, degreeOfParallelism, priority, logFilePatterns, related)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="degreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="logFilePatterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="related" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
      </Parameters>
      <Docs>
        <param name="type">(Hive または USql) は、現在のジョブのジョブの種類。
            使用可能な値が含まれます: 'USql'、'ハイブ'</param>
        <param name="properties">ジョブの特定プロパティです。</param>
        <param name="name">送信するジョブのフレンドリ名。</param>
        <param name="degreeOfParallelism">このジョブに使用する並列処理の次数。 場合 1 を 0 未満の値の設定は既定値は 0 より大きくにあります。</param>
        <param name="priority">現在のジョブに使用する優先度の値。 数値が小さいほど優先順位が高いがあります。 、既定では、ジョブは、1000 の優先順位を持ちます。 これは、0 より大きくなければなりません。</param>
        <param name="logFilePatterns">logFolder 内を検索するログ ファイル名パターンの一覧。 '*' は許可されている唯一の一致する文字。形式の例: jobExecution*.log または*mylog*.txt</param>
        <param name="related">定期的なジョブ関係情報のプロパティです。</param>
        <summary>
            CreateJobParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このジョブに使用する並列処理の次数を設定します。 場合 1 を 0 未満の値の設定は既定値は 0 より大きくにあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFilePatterns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; LogFilePatterns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; LogFilePatterns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.LogFilePatterns" />
      <MemberSignature Language="VB.NET" Value="Public Property LogFilePatterns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.LogFilePatterns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.LogFilePatterns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logFilePatterns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、logFolder 内を検索するログ ファイル名パターンの一覧を設定します。 '*' は許可されている唯一の一致する文字。形式の例: jobExecution*.log または*mylog*.txt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または送信するジョブのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在のジョブに使用する優先度の値を設定します。 数値が小さいほど優先順位が高いがあります。 既定では、ジョブが優先順位
            1000. これは、0 より大きくなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Related">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Related" />
      <MemberSignature Language="VB.NET" Value="Public Property Related As JobRelationshipProperties" />
      <MemberSignature Language="F#" Value="member this.Related : Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Related" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="related")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、定期的なジョブの関係情報のプロパティを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="createJobParameters.Validate " />
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