<Type Name="ElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ElasticPoolsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPool) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            操作することで、弾力性プールの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成または弾力性プールの更新の必須パラメーターです。
            </param>
        <summary>
            新しいエラスティック プールを作成するか、既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            操作することで、弾力性プールの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成または弾力性プールの更新の必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいエラスティック プールを作成するか、既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool BeginUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool BeginUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPoolUpdate) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            更新する弾力性プールの名前。
            </param>
        <param name="parameters">
            弾力性プールを更新するための必須パラメーターです。
            </param>
        <summary>
            既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            更新する弾力性プールの名前。
            </param>
        <param name="parameters">
            弾力性プールを更新するための必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool CreateOrUpdate (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool CreateOrUpdate(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPool) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            操作することで、弾力性プールの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成または弾力性プールの更新の必須パラメーターです。
            </param>
        <summary>
            新しいエラスティック プールを作成するか、既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPool parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPool,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPool" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            操作することで、弾力性プールの名前 (更新または作成した)。
            </param>
        <param name="parameters">
            作成または弾力性プールの更新の必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいエラスティック プールを作成するか、既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Delete (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            削除する弾力性プールの名前。
            </param>
        <summary>
            エラスティック プールを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            削除する弾力性プールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エラスティック プールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool Get (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool Get(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Get (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            取得する弾力性プールの名前。
            </param>
        <summary>
            エラスティック プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; GetAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; GetAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            取得する弾力性プールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エラスティック プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; ListByServer (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; ListByServer(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of ElasticPool)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <summary>
            サーバー内のエラスティック プールの一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
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
            サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サーバー内のエラスティック プールの一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt; ListMetricDefinitions(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitions(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinitions (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitions : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitions (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            弾力性プールの名前。
            </param>
        <summary>
            弾力性プールのメトリックの定義を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            弾力性プールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            弾力性プールのメトリックの定義を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt; ListMetrics(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetrics(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, filter As String) As IEnumerable(Of Metric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetrics (operations, resourceGroupName, serverName, elasticPoolName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            弾力性プールの名前。
            </param>
        <param name="filter">
            取得するメトリックのサブセットを記述する OData フィルター式。
            </param>
        <summary>
            弾力性プールのメトリックを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, elasticPoolName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            弾力性プールの名前。
            </param>
        <param name="filter">
            取得するメトリックのサブセットを記述する OData フィルター式。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            弾力性プールのメトリックを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ElasticPool Update (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ElasticPool Update(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IElasticPoolsOperations, resourceGroupName As String, serverName As String, elasticPoolName As String, parameters As ElasticPoolUpdate) As ElasticPool" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPool" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.Update (operations, resourceGroupName, serverName, elasticPoolName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            更新する弾力性プールの名前。
            </param>
        <param name="parameters">
            弾力性プールを更新するための必須パラメーターです。
            </param>
        <summary>
            既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPool&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
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
            サーバーの名前。
            </param>
        <param name="elasticPoolName">
            更新する弾力性プールの名前。
            </param>
        <param name="parameters">
            弾力性プールを更新するための必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のエラスティック プールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>