<Type Name="AddTaskCollectionTerminatedException" FullName="Microsoft.Azure.Batch.AddTaskCollectionTerminatedException">
  <TypeSignature Language="C#" Value="public class AddTaskCollectionTerminatedException : Microsoft.Azure.Batch.BatchClientException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddTaskCollectionTerminatedException extends Microsoft.Azure.Batch.BatchClientException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" />
  <TypeSignature Language="VB.NET" Value="Public Class AddTaskCollectionTerminatedException&#xA;Inherits BatchClientException" />
  <TypeSignature Language="F#" Value="type AddTaskCollectionTerminatedException = class&#xA;    inherit BatchClientException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            AddTaskCollection 操作が終了した場合にスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTaskResult">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AddTaskResult AddTaskResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AddTaskResult AddTaskResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException.AddTaskResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AddTaskResult As AddTaskResult" />
      <MemberSignature Language="F#" Value="member this.AddTaskResult : Microsoft.Azure.Batch.AddTaskResult" Usage="Microsoft.Azure.Batch.AddTaskCollectionTerminatedException.AddTaskResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException.AddTaskResult" />例外の原因となるタスクです。
            </summary>
        <value>To be added.</value>
        <remarks>
            複数のタスクを失敗した可能性があります。 完全な一覧を表示するのには、使用、<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>