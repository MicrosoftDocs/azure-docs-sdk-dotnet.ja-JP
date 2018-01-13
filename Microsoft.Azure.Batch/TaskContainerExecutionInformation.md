<Type Name="TaskContainerExecutionInformation" FullName="Microsoft.Azure.Batch.TaskContainerExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskContainerExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskContainerExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskContainerExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タスクを実行しているコンテナーに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーに関する詳細なエラー情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、使用可能な場合に、Docker サービスから詳細なエラーの文字列です。 Equivilant「docker 検査」によって返されるエラー フィールドにすることをお勧めします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Docker サービスに従って、コンテナーの状態です。 Equivilant「docker 検査」によって返されるステータス フィールドにすることをお勧めします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>