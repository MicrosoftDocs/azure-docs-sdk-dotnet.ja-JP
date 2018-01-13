<Type Name="TableUtils" FullName="Microsoft.Azure.Mobile.Server.Tables.TableUtils">
  <TypeSignature Language="C#" Value="public static class TableUtils" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableUtils extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.TableUtils" />
  <TypeSignature Language="VB.NET" Value="Public Class TableUtils" />
  <TypeSignature Language="F#" Value="type TableUtils = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            さまざまなユーティリティとテーブル用にヘルパー メソッドは、関連する機能。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyDeletedFilter&lt;TData&gt;">
      <MemberSignature Language="C#" Value="public static System.Linq.IQueryable&lt;TData&gt; ApplyDeletedFilter&lt;TData&gt; (System.Linq.IQueryable&lt;TData&gt; query, bool includeDeleted) where TData : class, Microsoft.Azure.Mobile.Server.Tables.ITableData;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Linq.IQueryable`1&lt;!!TData&gt; ApplyDeletedFilter&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt;(class System.Linq.IQueryable`1&lt;!!TData&gt; query, bool includeDeleted) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.ApplyDeletedFilter``1(System.Linq.IQueryable{``0},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ApplyDeletedFilter(Of TData As {Class, ITableData}) (query As IQueryable(Of TData), includeDeleted As Boolean) As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="static member ApplyDeletedFilter : System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * bool -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.ApplyDeletedFilter (query, includeDeleted)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TData">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TData&gt;" />
        <Parameter Name="includeDeleted" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <typeparam name="TData">データの種類</typeparam>
        <param name="query">クエリを実行します。</param>
        <param name="includeDeleted">フィルターが設定されているか</param>
        <summary>
            場合、削除されたレコードにフィルターを適用<paramref name="includeDeleted" />は true です。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedPropertyName">
      <MemberSignature Language="C#" Value="public static string DeletedPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DeletedPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.DeletedPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DeletedPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.DeletedPropertyName : string" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.DeletedPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <c>Deleted</c>プロパティ名。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNoQueryableLookupException">
      <MemberSignature Language="C#" Value="public static Exception GetNoQueryableLookupException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetNoQueryableLookupException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableLookupException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNoQueryableLookupException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetNoQueryableLookupException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableLookupException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType"><see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> の型。</param>
        <param name="method">これは、メソッド名をサポートします。</param>
        <summary>
            取得、<see cref="T:System.NotImplementedException" />ことを示す、指定された<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />はサポートしていません<see cref="T:System.Linq.IQueryable`1" />ベースの参照操作。
            </summary>
        <returns>新しい <see cref="T:System.NotImplementedException" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNoQueryableQueryException">
      <MemberSignature Language="C#" Value="public static Exception GetNoQueryableQueryException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetNoQueryableQueryException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableQueryException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNoQueryableQueryException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetNoQueryableQueryException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableQueryException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType"><see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> の型。</param>
        <param name="method">これは、メソッド名をサポートします。</param>
        <summary>
            取得、<see cref="T:System.NotImplementedException" />ことを示す、指定された<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />はサポートしていません<see cref="T:System.Linq.IQueryable`1" />ベースのクエリを実行します。
            </summary>
        <returns>新しい <see cref="T:System.NotImplementedException" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueryableOnlyLookupException">
      <MemberSignature Language="C#" Value="public static Exception GetQueryableOnlyLookupException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetQueryableOnlyLookupException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyLookupException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetQueryableOnlyLookupException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetQueryableOnlyLookupException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyLookupException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType"><see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> の型。</param>
        <param name="method">これは、メソッド名をサポートします。</param>
        <summary>
            取得、<see cref="T:System.NotImplementedException" />ことを示す、指定された<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />のみをサポートしている<see cref="T:System.Linq.IQueryable`1" />ベースの参照操作。
            </summary>
        <returns>新しい <see cref="T:System.NotImplementedException" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueryableOnlyQueryException">
      <MemberSignature Language="C#" Value="public static Exception GetQueryableOnlyQueryException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetQueryableOnlyQueryException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyQueryException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetQueryableOnlyQueryException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetQueryableOnlyQueryException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyQueryException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType"><see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> の型。</param>
        <param name="method">これは、メソッド名をサポートします。</param>
        <summary>
            取得、<see cref="T:System.NotImplementedException" />ことを示す、指定された<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />のみがサポート<see cref="T:System.Linq.IQueryable`1" />ベースのクエリを実行します。
            </summary>
        <returns>新しい <see cref="T:System.NotImplementedException" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResultSize">
      <MemberSignature Language="C#" Value="public static int GetResultSize (System.Web.Http.OData.Query.ODataQueryOptions query, System.Web.Http.OData.Query.ODataQuerySettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 GetResultSize(class System.Web.Http.OData.Query.ODataQueryOptions query, class System.Web.Http.OData.Query.ODataQuerySettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetResultSize(System.Web.Http.OData.Query.ODataQueryOptions,System.Web.Http.OData.Query.ODataQuerySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetResultSize (query As ODataQueryOptions, settings As ODataQuerySettings) As Integer" />
      <MemberSignature Language="F#" Value="static member GetResultSize : System.Web.Http.OData.Query.ODataQueryOptions * System.Web.Http.OData.Query.ODataQuerySettings -&gt; int" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetResultSize (query, settings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
        <Parameter Name="settings" Type="System.Web.Http.OData.Query.ODataQuerySettings" />
      </Parameters>
      <Docs>
        <param name="query">To be added.</param>
        <param name="settings">To be added.</param>
        <summary>
            効果的なクエリの結果サイズ意味、ページ サイズと最上位のパラメーターに基づいて、1 つのクエリ結果に含まれる要素の数が最大数を取得、 <paramref name="query" /><paramref name="settings" />です。
            </summary>
        <returns>指定されたクエリに対して有効なページ サイズ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageSize">
      <MemberSignature Language="C#" Value="public static int PageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 PageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.PageSize" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property PageSize As Integer" />
      <MemberSignature Language="F#" Value="member this.PageSize : int with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.PageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クエリの結果で返されないはレコードの最大数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionPropertyName">
      <MemberSignature Language="C#" Value="public static string VersionPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string VersionPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.VersionPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property VersionPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.VersionPropertyName : string" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.VersionPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<c>バージョン</c>プロパティ名。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>