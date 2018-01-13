<Type Name="IHubOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IHubOperations">
  <TypeSignature Language="C#" Value="public interface IHubOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHubOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IHubOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHubOperations" />
  <TypeSignature Language="F#" Value="type IHubOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ハブを管理するための操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="parameters">
            作成またはハブを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいハブ インスタンスを作成または既存のインスタンスを更新します。
            </summary>
        <returns>
            作成または更新ハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iHubOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="hubName">
            ハブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ハブ インスタンスを削除します。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="parameters">
            作成またはハブを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいハブ インスタンスを作成または既存のインスタンスを更新します。
            </summary>
        <returns>
            作成または更新ハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string hubName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string hubName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, hubName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="hubName">
            作成または更新するデータ ファクトリのハブの名前。
            </param>
        <param name="parameters">
            作成またはハブを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいハブ インスタンスを作成または既存のインスタンスを更新します。
            </summary>
        <returns>
            作成または更新ハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iHubOperations.DeleteAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="hubName">
            ハブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ハブ インスタンスを削除します。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;" Usage="iHubOperations.GetAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="hubName">
            ハブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ハブ インスタンスを取得します。
            </summary>
        <returns>
            Get ハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
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
        <summary>To be added.</summary>
        <returns>
            作成または更新ハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="iHubOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
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
            データ ファクトリの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがデータ ファクトリのハブ インスタンスの最初のページを取得します。
            </summary>
        <returns>
            リストのハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="iHubOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次のデータ ファクトリのハブ ページの url です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがデータ ファクトリのハブ インスタンスの次のページを取得します。
            </summary>
        <returns>
            リストのハブ操作の応答。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>