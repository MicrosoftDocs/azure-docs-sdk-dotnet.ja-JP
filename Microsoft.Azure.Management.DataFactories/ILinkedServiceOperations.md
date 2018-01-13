<Type Name="ILinkedServiceOperations" FullName="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations">
  <TypeSignature Language="C#" Value="public interface ILinkedServiceOperations : Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILinkedServiceOperations implements class Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILinkedServiceOperations&#xA;Implements ITypeRegistrationOperations(Of LinkedService)" />
  <TypeSignature Language="F#" Value="type ILinkedServiceOperations = interface&#xA;    interface ITypeRegistrationOperations&lt;LinkedService&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            データ ファクトリ linkedServices を管理するための操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
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
            作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはデータ ファクトリ linkedService を更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="linkedServiceName">
            データ ファクトリの作成または更新するリンクされたサービスの名前。
            </param>
        <param name="parameters">
            作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、生の JSON コンテンツを持つデータ ファクトリ linkedService を更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iLinkedServiceOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
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
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="linkedServiceName">
            一意のデータ ファクトリの linkedService 名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ファクトリの linkedService インスタンスを削除します。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
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
            作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはデータ ファクトリ linkedService を更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            データ ファクトリの名前。
            </param>
        <param name="linkedServiceName">
            データ ファクトリの作成または更新するリンクされたサービスの名前。
            </param>
        <param name="parameters">
            作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または、生の JSON コンテンツを持つデータ ファクトリ linkedService を更新します。
            </summary>
        <returns>
            作成または更新データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iLinkedServiceOperations.DeleteAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
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
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="linkedServiceName">
            一意のデータ ファクトリの linkedService 名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ファクトリの linkedService インスタンスを削除します。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;" Usage="iLinkedServiceOperations.GetAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            データ ファクトリのリソース グループ名。
            </param>
        <param name="dataFactoryName">
            一意のデータ ファクトリのインスタンス名です。
            </param>
        <param name="linkedServiceName">
            一意のデータ ファクトリの linkedService 名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ファクトリの linkedService インスタンスを取得します。
            </summary>
        <returns>
            Get データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
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
            リンクされたサービスの状態を作成または更新操作を取得します。
            </summary>
        <returns>
            作成または更新データ ファクトリ linkedService 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
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
            次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。
            </summary>
        <returns>
            一覧データ ファクトリ linkedServices 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次のリンクされたサービス ページの url です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。
            </summary>
        <returns>
            一覧データ ファクトリ linkedServices 操作応答です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>