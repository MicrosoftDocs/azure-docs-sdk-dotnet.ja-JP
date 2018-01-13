<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.BackupServices.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Azure バックアップ用拡張子に対してジョブ操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt; GetAsync (string resourceGroupName, string resourceName, string name, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt; GetAsync(string resourceGroupName, string resourceName, string name, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.GetAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt;" Usage="iJobOperations.GetAsync (resourceGroupName, resourceName, name, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="name">
            詳細を取得するジョブの名前。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のジョブの詳細を取得します。
            </summary>
        <returns>
            ジョブの詳細の操作の応答モデル
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt;" Usage="iJobOperations.ListAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMJobList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMJobQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="parameters">
            ジョブ クエリ パラメーター。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したフィルターによってクエリを実行するすべてのジョブの一覧を取得します。
            </summary>
        <returns>
            Powershell 応答オブジェクト
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; StopAsync (string resourceGroupName, string resourceName, string name, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; StopAsync(string resourceGroupName, string resourceName, string name, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IJobOperations.StopAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iJobOperations.StopAsync (resourceGroupName, resourceName, name, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="name">
            停止するか、ジョブの名前です。
            </param>
        <param name="customRequestHeaders">
            呼び出しにカスタムの要求ヘッダー。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブの取り消しをトリガーします。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>