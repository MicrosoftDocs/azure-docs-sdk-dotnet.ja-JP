<Type Name="BackupProtectableItemsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupProtectableItemsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupProtectableItemsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupProtectableItemsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupProtectableItemsOperationsExtensions = class" />
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
            BackupProtectableItemsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupProtectableItemsOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of BMSPOQueryObject) = null, Optional skipToken As String = null) As IPage(Of WorkloadProtectableItemResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
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
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="skipToken">
            skipToken フィルター。
            </param>
        <summary>
            クエリのフィルター処理と改ページ パラメーターに従ってサブスクリプション内の保護可能なオブジェクトのページング可能な一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
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
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="skipToken">
            skipToken フィルター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            クエリのフィルター処理と改ページ パラメーターに従ってサブスクリプション内の保護可能なオブジェクトのページング可能な一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupProtectableItemsOperations, nextPageLink As String) As IPage(Of WorkloadProtectableItemResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            クエリのフィルター処理と改ページ パラメーターに従ってサブスクリプション内の保護可能なオブジェクトのページング可能な一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectableItemsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectableItemsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            クエリのフィルター処理と改ページ パラメーターに従ってサブスクリプション内の保護可能なオブジェクトのページング可能な一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>