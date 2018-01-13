<Type Name="IDataFactoryOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations">
  <TypeSignature Language="C#" Value="public interface IDataFactoryOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataFactoryOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataFactoryOperations" />
  <TypeSignature Language="F#" Value="type IDataFactoryOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データ ファクトリを管理するための操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.BeginCreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.BeginCreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="parameters">
            作成または更新、データ ファクトリに必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはデータ ファクトリを更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.CreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.CreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="parameters">
            作成または更新、データ ファクトリに必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはデータ ファクトリを更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.DeleteAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataFactoryOperations.DeleteAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ファクトリのインスタンスを削除します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;" Usage="iDataFactoryOperations.GetAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ファクトリのインスタンスを取得します。
            </summary>
        <returns>
            データ ファクトリを取得操作応答します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            Begin 操作によって返される location 値です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Get Operation Status 操作では、指定された操作の状態を返します。 非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。
            </summary>
        <returns>
            作成または更新データ ファクトリ操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.ListAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがデータ ファクトリのインスタンスの最初のページを取得します。
            </summary>
        <returns>
            一覧データ ファクトリ操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次のデータ ファクトリのページの url です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがデータ ファクトリのインスタンスの次のページを取得します。
            </summary>
        <returns>
            一覧データ ファクトリ操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>