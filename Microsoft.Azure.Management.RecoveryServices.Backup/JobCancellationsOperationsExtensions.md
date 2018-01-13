<Type Name="JobCancellationsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobCancellationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobCancellationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobCancellationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobCancellationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            JobCancellationsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations operations, string vaultName, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations operations, string vaultName, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IJobCancellationsOperations, vaultName As String, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="jobName">
            キャンセルするジョブの名前です。
            </param>
        <summary>
            ジョブをキャンセルします。 これは非同期操作です。 取り消しの状態を確認するには、GetCancelOperationResult API を呼び出します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations operations, string vaultName, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations operations, string vaultName, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.JobCancellationsOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobCancellationsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="jobName">
            キャンセルするジョブの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブをキャンセルします。 これは非同期操作です。 取り消しの状態を確認するには、GetCancelOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>