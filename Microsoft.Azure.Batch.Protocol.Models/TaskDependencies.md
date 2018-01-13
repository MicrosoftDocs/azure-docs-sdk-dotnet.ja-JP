<Type Name="TaskDependencies" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies">
  <TypeSignature Language="C#" Value="public class TaskDependencies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDependencies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDependencies" />
  <TypeSignature Language="F#" Value="type TaskDependencies = class" />
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
            タスクの依存関係を指定します。 明示的に指定されているすべてのタスクまたは依存関係内で、範囲を依存タスクがスケジュールされる前に完了する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.#ctor" />
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
            TaskDependencies クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies (System.Collections.Generic.IList&lt;string&gt; taskIds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; taskIdRanges = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; taskIds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; taskIdRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskIdRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional taskIds As IList(Of String) = null, Optional taskIdRanges As IList(Of TaskIdRange) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskDependencies : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskDependencies (taskIds, taskIdRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="taskIdRanges" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt;" />
      </Parameters>
      <Docs>
        <param name="taskIds">タスクにこのタスクが依存している Id の一覧。 この一覧のすべてのタスクは、依存タスクをスケジュールする前に正常に完了する必要があります。</param>
        <param name="taskIdRanges">このタスクが依存しているタスクの ID 範囲の一覧。 依存タスクをスケジュールする前にすべての範囲内のすべてのタスクが正常に完了する必要があります。</param>
        <summary>
            TaskDependencies クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; TaskIdRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; TaskIdRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIdRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskIdRanges As IList(Of TaskIdRange)" />
      <MemberSignature Language="F#" Value="member this.TaskIdRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIdRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskIdRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このタスクが依存しているタスクの ID 範囲の一覧を設定します。
            依存タスクをスケジュールする前にすべての範囲内のすべてのタスクが正常に完了する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TaskIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TaskIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIds" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TaskIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクにこのタスクが依存している Id の一覧を設定します。 この一覧のすべてのタスクは、依存タスクをスケジュールする前に正常に完了する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>
            TaskIds コレクションには 64000 文字合計 (つまり、結合された長すべてのタスク Id) に制限されます。 TaskIds コレクションは、最大長を超えている場合は、エラー コード TaskDependencyListTooLong でタスクの追加要求が失敗します。 ここでは、タスク ID の範囲を代わりに使用を検討します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>