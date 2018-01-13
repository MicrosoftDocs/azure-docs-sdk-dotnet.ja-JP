<Type Name="AddTaskResult" FullName="Microsoft.Azure.Batch.AddTaskResult">
  <TypeSignature Language="C#" Value="public class AddTaskResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddTaskResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AddTaskResult" />
  <TypeSignature Language="F#" Value="type AddTaskResult = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            タスクのコレクションの一部として追加された 1 つのタスクの結果。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.BatchError Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.BatchError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As BatchError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.BatchError" Usage="Microsoft.Azure.Batch.AddTaskResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクを追加しようとしました。 キャッチされたエラーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.AddTaskResult.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正常に追加されたタスクに関連付けられた ETag を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.AddTaskResult.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正常に追加されたタスクに関連付けられている最終更新時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Batch.AddTaskResult.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正常に追加されたタスクの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int" Usage="Microsoft.Azure.Batch.AddTaskResult.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このタスクのタスクの追加操作が再試行された回数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.AddTaskStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.AddTaskStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As AddTaskStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Batch.Common.AddTaskStatus" Usage="Microsoft.Azure.Batch.AddTaskResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AddTaskStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            追加のタスクの要求の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask Task { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudTask Task" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.Task" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Task As CloudTask" />
      <MemberSignature Language="F#" Value="member this.Task : Microsoft.Azure.Batch.CloudTask" Usage="Microsoft.Azure.Batch.AddTaskResult.Task" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクの詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskResult.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string" Usage="Microsoft.Azure.Batch.AddTaskResult.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この結果が適用されるタスクの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AddTaskResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="addTaskResult.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトを表す文字列を返します。
            </summary>
        <returns>現在のオブジェクトを表す文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>