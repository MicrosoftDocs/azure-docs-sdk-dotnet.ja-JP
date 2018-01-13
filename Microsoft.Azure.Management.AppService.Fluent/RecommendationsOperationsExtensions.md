<Type Name="RecommendationsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RecommendationsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableAllForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableAllForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.DisableAllForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.DisableAllForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;DisableAllForWebAppAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="siteName">
            アプリの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリのすべての推奨設定を無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのすべての推奨設定を無効にします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt; GetRuleDetailsByWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt; GetRuleDetailsByWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync (operations, resourceGroupName, siteName, name, updateSeen, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;GetRuleDetailsByWebAppAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="siteName">
            アプリの名前です。
            </param>
        <param name="name">
            推奨設定の名前です。
            </param>
        <param name="updateSeen">
            指定&lt;コード&gt;true&lt;/code&gt;推奨設定オブジェクトの最後に表示されるタイムスタンプを更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリのリコメンデーション ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのリコメンデーション ルールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListAsync (operations, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="featured">
            指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。 既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。
            </param>
        <param name="filter">
            フィルターを指定するには、OData 構文を使用します。 例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションのすべての推奨事項を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべての推奨事項を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListHistoryForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListHistoryForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync (operations, resourceGroupName, siteName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListHistoryForWebAppAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="siteName">
            アプリの名前です。
            </param>
        <param name="filter">
            フィルターを指定するには、OData 構文を使用します。 例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListRecommendedRulesForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListRecommendedRulesForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync (operations, resourceGroupName, siteName, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListRecommendedRulesForWebAppAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="siteName">
            アプリの名前です。
            </param>
        <param name="featured">
            指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。 既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。
            </param>
        <param name="filter">
            フィルターに指定されたチャネルのみを返します。 フィルターを指定するには、OData 構文を使用します。 例: $filter = チャネル eq 'Api' またはチャネル eq '通知'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリのすべての推奨事項を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのすべての推奨事項を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ResetAllFiltersAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
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
            サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ResetAllFiltersForWebAppAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースが属するリソース グループの名前です。
            </param>
        <param name="siteName">
            アプリの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アプリのすべての推奨事項オプトアウトの設定をリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのすべての推奨事項オプトアウトの設定をリセットします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>