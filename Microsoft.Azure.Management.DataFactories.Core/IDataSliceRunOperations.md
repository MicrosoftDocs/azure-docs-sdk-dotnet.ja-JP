<Type Name="IDataSliceRunOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceRunOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceRunOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceRunOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceRunOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データ スライスの実行を管理するための操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string runId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="iDataSliceRunOperations.GetAsync (resourceGroupName, dataFactoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="runId">
            一意のデータ スライスの実行の id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ スライスの実行のインスタンスを取得します。
            </summary>
        <returns>
            Get 操作の応答のデータ スライスを実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (string resourceGroupName, string dataFactoryName, string dataSliceRunId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(string resourceGroupName, string dataFactoryName, string dataSliceRunId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.GetLogsAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLogsAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="iDataSliceRunOperations.GetLogsAsync (resourceGroupName, dataFactoryName, dataSliceRunId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="dataSliceRunId">
            一意のデータ スライスは、インスタンス id を実行します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ スライスの実行のログを取得します。
            </summary>
        <returns>
            データ スライスは、get ログ操作の応答を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="datasetName">
            一意のデータセットのインスタンス名です。
            </param>
        <param name="parameters">
            データセットのデータ スライスの一覧にフィルターを指定するためのパラメーターが実行されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページにリンクを使用してインスタンスを実行するデータ スライスの最初のページを取得します。
            </summary>
        <returns>
            一覧のデータ スライスは、操作の応答を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次のデータ スライスへの url は、ページを実行します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクを持つ実行のインスタンスの次のページを取得します。
            </summary>
        <returns>
            一覧のデータ スライスは、操作の応答を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>