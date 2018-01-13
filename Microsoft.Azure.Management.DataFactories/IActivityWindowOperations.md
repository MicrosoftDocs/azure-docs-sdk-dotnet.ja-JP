<Type Name="IActivityWindowOperations" FullName="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations">
  <TypeSignature Language="C#" Value="public interface IActivityWindowOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityWindowOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityWindowOperations" />
  <TypeSignature Language="F#" Value="type IActivityWindowOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アクティビティ ウィンドウの操作。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            パイプラインのアクティビティのパラメーターでアクティビティ windows 一覧。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            アクティビティ ウィンドウは、オプションのフィルター パラメーターを一覧表示します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            データセット パラメーターによってアクティビティ windows 一覧。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            パイプラインのパラメーターでアクティビティ windows 一覧。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            アクティビティの windows の次のページの URL です。
            </param>
        <param name="parameters">
            アクティビティ ウィンドウの一覧のフィルタ リングします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            アクティビティの windows の次のページの URL です。
            </param>
        <param name="parameters">
            アクティビティ ウィンドウの一覧のフィルタ リングします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            アクティビティの windows の次のページの URL です。
            </param>
        <param name="parameters">
            アクティビティ ウィンドウの一覧のフィルタ リングします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            アクティビティの windows の次のページの URL です。
            </param>
        <param name="parameters">
            アクティビティ ウィンドウの一覧のフィルタ リングします。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。
            </summary>
        <returns>
            リスト アクティビティ windows 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>