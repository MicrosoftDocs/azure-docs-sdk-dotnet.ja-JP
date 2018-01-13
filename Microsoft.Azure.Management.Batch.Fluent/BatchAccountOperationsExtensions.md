<Type Name="BatchAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BatchAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BatchAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BatchAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BatchAccountOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            BatchAccountOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            新しい Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            領域内で一意でなければなりません Batch アカウントの名前。 Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。 この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。 例: http://accountname.region.batch.azure.com/ です。
            </param>
        <param name="parameters">
            アカウントの作成に追加のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したパラメーターを使用して、新しい Batch アカウントを作成します。 既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するバッチ アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            削除するアカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Batch アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            新しい Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            領域内で一意でなければなりません Batch アカウントの名前。 Batch アカウント名は 3 ~ 24 文字にする必要があり、数字と小文字のアルファベットだけを使用する必要があります。 この名前は、バッチ サービスは、アカウントを作成する領域のアクセスに使用される DNS 名の一部として使用されます。 例: http://accountname.region.batch.azure.com/ です。
            </param>
        <param name="parameters">
            アカウントの作成に追加のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したパラメーターを使用して、新しい Batch アカウントを作成します。 既存のアカウントは、この API を更新できませんおよび更新バッチ アカウントの API を代わりに更新する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountDeleteHeadersInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するバッチ アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            削除するアカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Batch アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; GetAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            アカウントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたバッチ アカウントに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; GetKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.GetKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;GetKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            アカウントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたバッチ アカウントのアカウント キーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースの名前を一覧表示するバッチ アカウントを持つをグループ化します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内で関連付けられているバッチ アカウントに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            指定されたリソース グループ内で関連付けられているバッチ アカウントに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
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
            サブスクリプションに関連付けられているバッチ アカウントに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountRegenerateKeyParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="accountName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynchronizeAutoStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SynchronizeAutoStorageKeysAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SynchronizeAutoStorageKeysAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.SynchronizeAutoStorageKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;SynchronizeAutoStorageKeysAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたバッチ アカウント用に構成された自動ストレージ アカウントのアクセス キーを同期します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.BatchAccountOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IBatchAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            アカウントの名前です。
            </param>
        <param name="parameters">
            アカウントの更新プログラムの追加のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のバッチ アカウントのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>