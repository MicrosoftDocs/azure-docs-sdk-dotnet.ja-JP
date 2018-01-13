<Type Name="WorkspacesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WorkspacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WorkspacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WorkspacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WorkspacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            WorkspacesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="parameters">
            作成またはワークスペースを更新するために必要なパラメーターです。
            </param>
        <summary>
            作成またはワークスペースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="parameters">
            作成またはワークスペースを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはワークスペースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="parameters">
            検索クエリを実行するために必要なパラメーターです。
            </param>
        <summary>
            指定されたワークスペースの検索を送信します。 応答は、検索を追跡するための id が含まれます。 ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginGetSearchResultsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="parameters">
            検索クエリを実行するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたワークスペースの検索を送信します。 応答は、検索を追跡するための id が含まれます。 ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="parameters">
            作成またはワークスペースを更新するために必要なパラメーターです。
            </param>
        <summary>
            作成またはワークスペースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="parameters">
            作成またはワークスペースを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはワークスペースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <summary>
            ワークスペースのインスタンスを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワークスペースのインスタンスを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void DisableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="intelligencePackName">
            無効にするインテリジェンス パックの名前。
            </param>
        <summary>
            指定されたワークスペースのインテリジェンス パックを無効にします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DisableIntelligencePackAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="intelligencePackName">
            無効にするインテリジェンス パックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたワークスペースのインテリジェンス パックを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void EnableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="intelligencePackName">
            有効にするインテリジェンス パックの名前。
            </param>
        <summary>
            指定されたワークスペースのインテリジェンス パックを有効にします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;EnableIntelligencePackAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="intelligencePackName">
            有効にするインテリジェンス パックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたワークスペースのインテリジェンス パックを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As Workspace" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <summary>
            ワークスペースのインスタンスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ワークスペースのリソース グループ名。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワークスペースのインスタンスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSchema (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SearchGetSchemaResponse" />
      <MemberSignature Language="F#" Value="static member GetSchema : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <summary>
            指定されたワークスペースのスキーマを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSchemaAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSchemaAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたワークスペースのスキーマを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member GetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="parameters">
            検索クエリを実行するために必要なパラメーターです。
            </param>
        <summary>
            指定されたワークスペースの検索を送信します。 応答は、検索を追跡するための id が含まれます。 ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSearchResultsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="parameters">
            検索クエリを実行するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたワークスペースの検索を送信します。 応答は、検索を追跡するための id が含まれます。 ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSharedKeys (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SharedKeys" />
      <MemberSignature Language="F#" Value="static member GetSharedKeys : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <summary>
            ワークスペースの共有キーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeysAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSharedKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワークスペースの共有キーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWorkspacesOperations) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            サブスクリプション内のワークスペースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
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
            サブスクリプション内のワークスペースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IWorkspacesOperations, resourceGroupName As String) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <summary>
            リソース グループ内のワークスペースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内のワークスペースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacks">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListIntelligencePacks (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IList(Of IntelligencePack)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacks : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <summary>
            リスト、すべてのインテリジェンス パック可能かどうか有効または無効にした、特定のワークスペースのします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacksAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListIntelligencePacksAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リスト、すべてのインテリジェンス パック可能かどうか有効または無効にした、特定のワークスペースのします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLinkTargets (operations As IWorkspacesOperations) As IList(Of LinkTarget)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargets : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            一覧を取得する現在のユーザーがいるワークスペースの管理者特権とは、Azure サブスクリプションに関連付けられていません。 Url の subscriptionId パラメーターは無視されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargetsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListLinkTargetsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
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
            一覧を取得する現在のユーザーがいるワークスペースの管理者特権とは、Azure サブスクリプションに関連付けられていません。 Url の subscriptionId パラメーターは無視されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroups">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListManagementGroups (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of ManagementGroup)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroups : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <summary>
            ワークスペースに接続されている管理グループの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroupsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListManagementGroupsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワークスペースに接続されている管理グループの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of UsageMetric)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <summary>
            ワークスペースの使用状況メトリックの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListUsagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ワークスペースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ワークスペースの使用状況メトリックの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, id As String) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults (operations, resourceGroupName, workspaceName, id)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="id">
            検索結果の更新を持っているの id。 GetResults 呼び出しの応答から id を取得できます。
            </param>
        <summary>
            更新された特定の検索クエリの検索結果を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync (operations, resourceGroupName, workspaceName, id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;UpdateSearchResultsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            ログ分析ワークスペース名
            </param>
        <param name="id">
            検索結果の更新を持っているの id。 GetResults 呼び出しの応答から id を取得できます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新された特定の検索クエリの検索結果を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>