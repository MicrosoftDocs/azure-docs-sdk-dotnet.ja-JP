<Type Name="DatabasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabasesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DatabasesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            処理される Azure SQL データベースの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成またはデータベースの更新の必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。
            場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAllowDataLossAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            フェールオーバーを行うレプリケーション リンクの ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            フェールオーバーを行うレプリケーション リンクの ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginPauseDataWarehouseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            一時停止する Azure SQL Data Warehouse データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL Data Warehouse データベースを一時停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginResumeDataWarehouseAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            再開する Azure SQL Data Warehouse データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL Data Warehouse データベースを再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            処理される Azure SQL データベースの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成またはデータベースの更新の必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。
            場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, status, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateTransparentDataEncryptionConfigurationAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータ暗号化を適用するための設定、Azure SQL データベースの名前。
            </param>
        <param name="status">
            Azure SQL データベース透過的なデータ暗号化の状態です。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、Azure SQL データベース透過的なデータ暗号化操作を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            削除する Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteReplicationLinkAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            削除するレプリケーション リンクがある Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            削除するレプリケーション リンクの ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された ID と Azure SQL データベース レプリケーション リンクを削除します フェールオーバー中には実行できません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAllowDataLossAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            フェールオーバーを行うレプリケーション リンクの ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            フェールオーバーを行うレプリケーション リンクの ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            取得する Azure SQL データベースの名前。
            </param>
        <param name="expand">
            コンマ区切りの応答で展開する子オブジェクトの一覧です。
            使用可能なプロパティ: serviceTierAdvisors、upgradeHint、transparentDataEncryption です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetReplicationLinkAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            リンクを取得する Azure SQL データベースの名前。
            </param>
        <param name="linkId">
            レプリケーション リンク ID を取得します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベース レプリケーション リンクに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTierAdvisorAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServiceTierAdvisorAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetServiceTierAdvisorAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            データベースの名前。
            </param>
        <param name="serviceTierAdvisorName">
            サービス層アドバイザーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス層アドバイザーに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetTransparentDataEncryptionConfigurationAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータ暗号化を適用する Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースの透過的なデータ暗号化応答を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListByServerAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListReplicationLinksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListReplicationLinksAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListReplicationLinksAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            リンクを取得する Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベース レプリケーション リンクに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRestorePointsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRestorePointsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListRestorePointsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            使用可能な取得する対象の Azure SQL データベースの名前は、ポイントを復元します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースの一覧を返しますでは、ポイントを復元します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceTierAdvisorsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceTierAdvisorsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListServiceTierAdvisorsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したデータベースのサービス層アドバイザーに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTransparentDataEncryptionActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTransparentDataEncryptionActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListTransparentDataEncryptionActivityAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            透過的なデータ暗号化を適用する Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベース透過的なデータの暗号化活動応答を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListUsagesAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースの使用状況に関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;PauseDataWarehouseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            一時停止する Azure SQL Data Warehouse データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL Data Warehouse データベースを一時停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ResumeDataWarehouseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="databaseName">
            再開する Azure SQL Data Warehouse データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL Data Warehouse データベースを再開します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>