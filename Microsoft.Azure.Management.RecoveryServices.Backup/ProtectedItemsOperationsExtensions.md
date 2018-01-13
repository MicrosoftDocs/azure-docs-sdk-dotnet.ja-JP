<Type Name="ProtectedItemsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemsOperationsExtensions = class" />
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
            ProtectedItemsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static void CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateOrUpdate (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, parameters As ProtectedItemResource)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
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
        <param name="fabricName">
            バックアップ項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップ アイテムに関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            バックアップする項目の名前。
            </param>
        <param name="parameters">
            リソース アイテムのバックアップ
            </param>
        <summary>
            項目のバックアップを有効またはに既にバックアップ項目のバックアップ ポリシー情報を変更します。 これは非同期操作です。 操作の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
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
        <param name="fabricName">
            バックアップ項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップ アイテムに関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            バックアップする項目の名前。
            </param>
        <param name="parameters">
            リソース アイテムのバックアップ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            項目のバックアップを有効またはに既にバックアップ項目のバックアップ ポリシー情報を変更します。 これは非同期操作です。 操作の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            削除する項目をバックアップします。
            </param>
        <summary>
            コンテナー内の項目のバックアップを無効にするために使用します。 これは非同期操作です。 要求の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            削除する項目をバックアップします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            コンテナー内の項目のバックアップを無効にするために使用します。 これは非同期操作です。 要求の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, Optional odataQuery As ODataQuery(Of GetProtectedItemQueryObject) = null) As ProtectedItemResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            バックアップの詳細については、フェッチするのには項目の名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            バックアップ項目の詳細を提供します。 これは非同期操作です。 操作の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            バックアップの詳細については、フェッチするのには項目の名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            バックアップ項目の詳細を提供します。 これは非同期操作です。 操作の状態を確認するには、GetItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>