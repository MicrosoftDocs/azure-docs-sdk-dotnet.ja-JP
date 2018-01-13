<Type Name="DataLakeStoreAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataLakeStoreAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DataLakeStoreAccountsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String, Optional parameters As AddDataLakeStoreParameters = null)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加する、Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            追加する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの詳細。
            </param>
        <summary>
            含める追加の Data Lake Store アカウントに指定された Data Lake Analytics アカウントを更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加する、Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            追加する Data Lake Store アカウントの名前。
            </param>
        <param name="parameters">
            Data Lake Store アカウントの詳細。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            含める追加の Data Lake Store アカウントに指定された Data Lake Analytics アカウントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを削除する Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            削除する Data Lake Store アカウントの名前
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除する指定された Data Lake Analytics アカウントを更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを削除する Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            削除する Data Lake Store アカウントの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントを削除する指定された Data Lake Analytics アカウントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String) As DataLakeStoreAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            取得する Data Lake Store アカウントの名前
            </param>
        <summary>
            指定された Data Lake Analytics アカウントの指定された Data Lake Store アカウントの詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。
            </param>
        <param name="dataLakeStoreAccountName">
            取得する Data Lake Store アカウントの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントの指定された Data Lake Store アカウントの詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of DataLakeStoreAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            名前、Data Lake Analytics アカウントの Data Lake Store アカウントを一覧表示します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <summary>
            Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            名前、Data Lake Analytics アカウントの Data Lake Store アカウントを一覧表示します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IDataLakeStoreAccountsOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
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
            Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
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
            Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。 応答には、存在する場合、次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>