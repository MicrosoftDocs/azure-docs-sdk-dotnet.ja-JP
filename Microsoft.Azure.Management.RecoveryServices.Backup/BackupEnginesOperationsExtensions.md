<Type Name="BackupEnginesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupEnginesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupEnginesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupEnginesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupEnginesOperationsExtensions = class" />
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
            BackupEnginesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupEnginesOperations, vaultName As String, resourceGroupName As String, backupEngineName As String, Optional odataQuery As ODataQuery(Of BMSBackupEngineQueryObject) = null, Optional skipToken As String = null) As BackupEngineBaseResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.Get (operations, vaultName, resourceGroupName, backupEngineName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt;" />
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
        <param name="backupEngineName">
            バックアップの管理サーバーの名前です。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="skipToken">
            skipToken フィルター。
            </param>
        <summary>
            Recovery Services コンテナーにバックアップ管理サーバーの登録を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, string backupEngineName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, backupEngineName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEngineQueryObject&gt;" />
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
        <param name="backupEngineName">
            バックアップの管理サーバーの名前です。
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
            Recovery Services コンテナーにバックアップ管理サーバーの登録を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupEnginesOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of BMSBackupEnginesQueryObject) = null, Optional skipToken As String = null) As IPage(Of BackupEngineBaseResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt;" />
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
            Recovery Services コンテナーに登録されているバックアップ管理サーバー。 サーバーのページング可能な一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupEnginesQueryObject&gt;" />
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
            Recovery Services コンテナーに登録されているバックアップ管理サーバー。 サーバーのページング可能な一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupEnginesOperations, nextPageLink As String) As IPage(Of BackupEngineBaseResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
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
            Recovery Services コンテナーに登録されているバックアップ管理サーバー。 サーバーのページング可能な一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupEnginesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBaseResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupEnginesOperations" RefType="this" />
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
            Recovery Services コンテナーに登録されているバックアップ管理サーバー。 サーバーのページング可能な一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>