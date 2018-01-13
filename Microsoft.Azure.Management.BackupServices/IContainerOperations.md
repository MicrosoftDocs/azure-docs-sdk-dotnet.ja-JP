<Type Name="IContainerOperations" FullName="Microsoft.Azure.Management.BackupServices.IContainerOperations">
  <TypeSignature Language="C#" Value="public interface IContainerOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IContainerOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerOperations" />
  <TypeSignature Language="F#" Value="type IContainerOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Azure Backup の拡張機能のコンテナーの操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;" Usage="iContainerOperations.ListAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="parameters">
            コンテナーのクエリのパラメーターです。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。
            </summary>
        <returns>
            CSMContainerListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RefreshAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RefreshAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この検出をトリガーします。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RegisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RegisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            登録するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コンテナーを登録します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.UnregisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.UnregisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            登録を解除するコンテナーです。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コンテナーの登録を解除します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>