<Type Name="IDataSliceOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データ スライスを管理するための操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="tableName">
            一意テーブルのインスタンス名。
            </param>
        <param name="parameters">
            テーブルのデータ スライスを一覧表示する方法を指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページにリンクを使用してデータ スライスのインスタンスの最初のページを取得します。
            </summary>
        <returns>
            リストのデータは、操作の応答をスライスします。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次のデータ スライスのページの url です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページにリンクを使用してデータ スライスのインスタンスの次のページを取得します。
            </summary>
        <returns>
            リストのデータは、操作の応答をスライスします。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.SetStatusAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStatusAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataSliceOperations.SetStatusAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="tableName">
            一意テーブルのインスタンス名。
            </param>
        <param name="parameters">
            データ スライスの状態を設定するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のテーブルに対しての時間範囲には、データ スライスの状態を設定します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>