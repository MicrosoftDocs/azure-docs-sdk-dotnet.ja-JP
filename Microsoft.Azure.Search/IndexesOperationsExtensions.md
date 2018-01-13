<Type Name="IndexesOperationsExtensions" FullName="Microsoft.Azure.Search.IndexesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IndexesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IndexesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            インデックスを管理するための操作です。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Index-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Analyze">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AnalyzeResult Analyze (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AnalyzeResult Analyze(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Analyze : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.AnalyzeResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze (operations, indexName, request, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzeResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            アナライザーのテスト対象のインデックスの名前。
            </param>
        <param name="request">
            テキストやアナライザー、分析コンポーネントをテストします。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            アナライザーがトークンにテキストを分割する方法を示しています。
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnalyzeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AnalyzeAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync (operations, indexName, request, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;AnalyzeAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            アナライザーのテスト対象のインデックスの名前。
            </param>
        <param name="request">
            テキストやアナライザー、分析コンポーネントをテストします。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アナライザーがトークンにテキストを分割する方法を示しています。
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Create (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Create(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Create(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Create (operations, index, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="index">
            作成するインデックスの定義。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            新しい Azure Search インデックスを作成します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync (operations, index, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="index">
            作成するインデックスの定義。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure Search インデックスを作成します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。 これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            インデックスを作成または更新の定義。
            </param>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。
            これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。 これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            インデックスを作成または更新の定義。
            </param>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。
            これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Delete(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Delete (operations, indexName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            削除するインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスとが含まれているすべてのドキュメントを削除します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync (operations, indexName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;DeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            削除するインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスとが含まれているすべてのドキュメントを削除します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Exists(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Exists (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            インデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。
            </summary>
        <returns>
          <c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            インデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。
            </summary>
        <returns>
          <c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Get (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Get(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Get(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Get (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            取得するインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search からインデックス定義を取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; GetAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; GetAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            取得するインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search からインデックス定義を取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member GetStatistics : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexGetStatisticsResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexGetStatisticsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            統計情報を取得する対象のインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatisticsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetStatisticsAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="indexName">
            統計情報を取得する対象のインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexListResult List (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexListResult List(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.List(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexListResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.List (operations, select, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="select">
            取得するインデックスの定義のプロパティを選択します。 JSON プロパティ名のコンマ区切りリストとして指定または ' *' のすべてのプロパティです。
            既定値は、すべてのプロパティです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync (operations, select, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="select">
            取得するインデックスの定義のプロパティを選択します。 JSON プロパティ名のコンマ区切りリストとして指定または ' *' のすべてのプロパティです。
            既定値は、すべてのプロパティです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNames">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; ListNames (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; ListNames(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListNames : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search サービスの使用可能なすべてのインデックスの名前を一覧表示します。 このときに使用 List() の代わりにのみ必要なインデックスを作成する名前。 帯域幅とリソースの使用率は、検索サービスに多数のインデックスがある場合に特にに保存されます。
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            Search サービスのすべてのインデックス名の一覧。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNamesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt; ListNamesAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;string&gt;&gt; ListNamesAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNamesAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListNamesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search サービスの使用可能なすべてのインデックスの名前を一覧表示します。 このときに使用 List() の代わりにのみ必要なインデックスを作成する名前。 帯域幅とリソースの使用率は、検索サービスに多数のインデックスがある場合に特にに保存されます。
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            Search サービスのすべてのインデックス名の一覧。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>