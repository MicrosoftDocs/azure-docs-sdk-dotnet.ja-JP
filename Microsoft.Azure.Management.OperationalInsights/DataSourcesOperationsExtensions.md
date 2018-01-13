<Type Name="DataSourcesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourcesOperationsExtensions = class" />
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
            DataSourcesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String, parameters As DataSource) As DataSource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, dataSourceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            データ ソースを格納する、ログ分析ワークスペースの名前
            </param>
        <param name="dataSourceName">
            データ ソースのリソースの名前。
            </param>
        <param name="parameters">
            作成またはデータ ソースを更新するために必要なパラメーターです。
            </param>
        <summary>
            作成またはデータ ソースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, dataSourceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
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
            データ ソースを格納する、ログ分析ワークスペースの名前
            </param>
        <param name="dataSourceName">
            データ ソースのリソースの名前。
            </param>
        <param name="parameters">
            作成またはデータ ソースを更新するために必要なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはデータ ソースを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            データ ソースを含むログ分析ワークスペースの名前です。
            </param>
        <param name="dataSourceName">
            データ ソースの名前です。
            </param>
        <summary>
            データ ソースのインスタンスを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
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
            データ ソースを含むログ分析ワークスペースの名前です。
            </param>
        <param name="dataSourceName">
            データ ソースの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ソースのインスタンスを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String) As DataSource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            データ ソースを含むログ分析ワークスペースの名前です。
            </param>
        <param name="dataSourceName">
            データソースの名前
            </param>
        <summary>
            データ ソース インスタンスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
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
            データ ソースを含むログ分析ワークスペースの名前です。
            </param>
        <param name="dataSourceName">
            データソースの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データ ソース インスタンスを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As IDataSourcesOperations, odataQuery As ODataQuery(Of DataSourceFilter), resourceGroupName As String, workspaceName As String, Optional skiptoken As String = null) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace (operations, odataQuery, resourceGroupName, workspaceName, skiptoken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            データ ソースを含むワークスペースです。
            </param>
        <param name="skiptoken">
            データ ソース インスタンスのコレクションの開始点です。
            </param>
        <summary>
            次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync (operations, odataQuery, resourceGroupName, workspaceName, skiptoken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="resourceGroupName">
            取得するリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="workspaceName">
            データ ソースを含むワークスペースです。
            </param>
        <param name="skiptoken">
            データ ソース インスタンスのコレクションの開始点です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspaceNext (operations As IDataSourcesOperations, nextPageLink As String) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNext : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNextAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
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
            次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>