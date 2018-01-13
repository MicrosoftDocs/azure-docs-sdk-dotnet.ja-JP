<Type Name="TrustedIdProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TrustedIdProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TrustedIdProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TrustedIdProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TrustedIdProvidersOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String, parameters As TrustedIdProvider) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, trustedIdProviderName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加または置き換える信頼できる id プロバイダーの名前。
            </param>
        <param name="trustedIdProviderName">
            信頼できる id プロバイダーの名前。 これは、アカウント内のプロバイダーの差別化を使用されます。
            </param>
        <param name="parameters">
            信頼できる id プロバイダーを作成または指定されたパラメーター。
            </param>
        <summary>
            作成するか、指定された信頼できる id プロバイダーを更新します。 この新しいプロバイダーを更新中に、信頼できる id プロバイダー、指定した名前は置き換えられます
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, trustedIdProviderName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加または置き換える信頼できる id プロバイダーの名前。
            </param>
        <param name="trustedIdProviderName">
            信頼できる id プロバイダーの名前。 これは、アカウント内のプロバイダーの差別化を使用されます。
            </param>
        <param name="parameters">
            信頼できる id プロバイダーを作成または指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定された信頼できる id プロバイダーを更新します。 この新しいプロバイダーを更新中に、信頼できる id プロバイダー、指定した名前は置き換えられます
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Delete (operations, resourceGroupName, accountName, trustedIdProviderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーを削除する Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            削除する信頼できる id プロバイダーの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントから指定された信頼できる id プロバイダーを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, trustedIdProviderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーを削除する Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            削除する信頼できる id プロバイダーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントから指定された信頼できる id プロバイダーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Get (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Get(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Get (operations, resourceGroupName, accountName, trustedIdProviderName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            取得する信頼できる id プロバイダーの名前。
            </param>
        <summary>
            指定された Data Lake Store 信頼できる id プロバイダーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, trustedIdProviderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            取得する信頼できる id プロバイダーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store 信頼できる id プロバイダーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String) As IPage(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As ITrustedIdProvidersOperations, nextPageLink As String) As IPage(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
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
            指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
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
            指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Update (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider Update(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ITrustedIdProvidersOperations, resourceGroupName As String, accountName As String, trustedIdProviderName As String, Optional parameters As UpdateTrustedIdProviderParameters = null) As TrustedIdProvider" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.Update (operations, resourceGroupName, accountName, trustedIdProviderName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーを更新するために、Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            信頼できる id プロバイダーの名前。 これは、アカウント内のプロバイダーの差別化を使用されます。
            </param>
        <param name="parameters">
            信頼できる id プロバイダーを更新する指定されたパラメーター。
            </param>
        <summary>
            指定された信頼できる id プロバイダーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations operations, string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, trustedIdProviderName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.TrustedIdProvidersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            信頼できる id プロバイダーを更新するために、Data Lake Store アカウントの名前。
            </param>
        <param name="trustedIdProviderName">
            信頼できる id プロバイダーの名前。 これは、アカウント内のプロバイダーの差別化を使用されます。
            </param>
        <param name="parameters">
            信頼できる id プロバイダーを更新する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された信頼できる id プロバイダーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>