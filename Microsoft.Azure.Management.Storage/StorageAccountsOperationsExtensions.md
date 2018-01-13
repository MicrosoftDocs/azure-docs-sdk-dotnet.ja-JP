<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            StorageAccountsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            作成したアカウントを提供するパラメーターです。
            </param>
        <summary>
            指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。
            アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。 アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            作成したアカウントを提供するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。
            アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。 アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IStorageAccountsOperations, name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability (operations, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            ストレージ アカウント名。
            </param>
        <summary>
            ストレージ アカウント名が有効で既に使用されていないことを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            ストレージ アカウント名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストレージ アカウント名が有効で既に使用されていないことを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Create (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Create(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            作成したアカウントを提供するパラメーターです。
            </param>
        <summary>
            指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。
            アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。 アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            作成したアカウントを提供するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。
            アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。 アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <summary>
            Microsoft Azure でストレージ アカウントを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Microsoft Azure でストレージ アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetProperties (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member GetProperties : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <summary>
            指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。 ListKeys 操作は、記憶域のキーの取得を使用する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。 ListKeys 操作は、記憶域のキーの取得を使用する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List(Microsoft.Azure.Management.Storage.IStorageAccountsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStorageAccountsOperations) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Storage.IStorageAccountsOperations -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。 ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAccountSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As AccountSasParameters) As ListAccountSasResponse" />
      <MemberSignature Language="F#" Value="static member ListAccountSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            ストレージ アカウントの一覧の SAS の資格情報を提供するパラメーターです。
            </param>
        <summary>
            ストレージ アカウントの SAS の資格情報を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAccountSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAccountSASAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            ストレージ アカウントの一覧の SAS の資格情報を提供するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストレージ アカウントの SAS の資格情報を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。 ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStorageAccountsOperations, resourceGroupName As String) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <summary>
            指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。
            ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。
            ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <summary>
            指定されたストレージ アカウントのアクセス キーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントのアクセス キーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListServiceSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As ServiceSasParameters) As ListServiceSasResponse" />
      <MemberSignature Language="F#" Value="static member ListServiceSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            リスト サービスの SAS の資格情報を提供するパラメーターです。
            </param>
        <summary>
            特定のリソースのサービスの SAS 資格情報を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListServiceSASAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            リスト サービスの SAS の資格情報を提供するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のリソースのサービスの SAS 資格情報を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, keyName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey (operations, resourceGroupName, accountName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="keyName">
            再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。
            </param>
        <summary>
            指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="keyName">
            再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Update (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Update(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountUpdateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            更新されたアカウントを提供するパラメーターです。
            </param>
        <summary>
            更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。 カスタム ドメインにアカウントをマップにも使用できます。 ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。 古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。 複数のプロパティの更新はサポートされています。 この呼び出しでは、ストレージ アカウントのキーは変更されません。 ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。 作成後は、ストレージ アカウントの名前と場所を変更できません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="parameters">
            更新されたアカウントを提供するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。 カスタム ドメインにアカウントをマップにも使用できます。 ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。 古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。 複数のプロパティの更新はサポートされています。 この呼び出しでは、ストレージ アカウントのキーは変更されません。 ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。 作成後は、ストレージ アカウントの名前と場所を変更できません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>