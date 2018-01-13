<Type Name="JobScheduleAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter">
  <TypeSignature Language="C#" Value="public class JobScheduleAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleAddParameter" />
  <TypeSignature Language="F#" Value="type JobScheduleAddParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            定期的なジョブのジョブと各ジョブの作成に使用される仕様を実行するタイミングを指定することにより、ジョブ スケジュールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobScheduleAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleAddParameter (string id, Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, string displayName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, class Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, string displayName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.Schedule,Microsoft.Azure.Batch.Protocol.Models.JobSpecification,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter : string * Microsoft.Azure.Batch.Protocol.Models.Schedule * Microsoft.Azure.Batch.Protocol.Models.JobSpecification * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter (id, schedule, jobSpecification, displayName, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Protocol.Models.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="id">アカウント内でスケジュールを一意に識別する文字列。</param>
        <param name="schedule">これに基づいてジョブを作成するスケジュールです。</param>
        <param name="jobSpecification">このスケジュールを作成するジョブの詳細。</param>
        <param name="displayName">スケジュールの表示名。</param>
        <param name="metadata">メタデータとしてスケジュールに関連付けられている名前と値のペアの一覧。</param>
        <summary>
            JobScheduleAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケジュールの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウント内でスケジュールを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。 ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるだけ、アカウント内の 2 つの Id はない必要があります)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.JobSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このスケジュールを作成するジョブの詳細を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてスケジュールに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Protocol.Models.Schedule with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Schedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこれに基づいてジョブを作成するスケジュールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobScheduleAddParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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