<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name"></param>
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
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
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
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="accountName">
            指定されたリソース グループ内にあるストレージ アカウントの名前。
            ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。
            </param>
        <param name="keyName"></param>
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
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
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