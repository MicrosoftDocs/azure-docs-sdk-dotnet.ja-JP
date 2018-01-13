<Type Name="RecommendationsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="DisableAllForWebApp">
      <MemberSignature Language="C#" Value="public static void DisableAllForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableAllForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableAllForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
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
        <summary>
            アプリのすべての推奨設定を無効にします。
            </summary>
        <remarks>
            アプリのすべての推奨設定を無効にします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAllForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableAllForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableAllForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;DisableAllForWebAppAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="GetRuleDetailsByWebApp">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRuleDetailsByWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, name As String, Optional updateSeen As Nullable(Of Boolean) = null) As RecommendationRule" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp (operations, resourceGroupName, siteName, name, updateSeen)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.RecommendationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
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
        <summary>
            アプリのリコメンデーション ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのリコメンデーション ルールを取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync (operations, resourceGroupName, siteName, name, updateSeen, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;GetRuleDetailsByWebAppAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecommendationsOperations, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List (operations, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
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
        <summary>
            サブスクリプションのすべての推奨事項を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サブスクリプションのすべての推奨事項を一覧表示します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync (operations, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="ListHistoryForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHistoryForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp (operations, resourceGroupName, siteName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
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
        <summary>
            過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync (operations, resourceGroupName, siteName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListHistoryForWebAppAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="ListRecommendedRulesForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendedRulesForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp (operations, resourceGroupName, siteName, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
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
        <summary>
            アプリのすべての推奨事項を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アプリのすべての推奨事項を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync (operations, resourceGroupName, siteName, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListRecommendedRulesForWebAppAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="ResetAllFilters">
      <MemberSignature Language="C#" Value="public static void ResetAllFilters (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFilters(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters(Microsoft.Azure.Management.WebSites.IRecommendationsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFilters (operations As IRecommendationsOperations)" />
      <MemberSignature Language="F#" Value="static member ResetAllFilters : Microsoft.Azure.Management.WebSites.IRecommendationsOperations -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。
            </summary>
        <remarks>
            サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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
    <Member MemberName="ResetAllFiltersForWebApp">
      <MemberSignature Language="C#" Value="public static void ResetAllFiltersForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFiltersForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFiltersForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
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
        <summary>
            アプリのすべての推奨事項オプトアウトの設定をリセットします。
            </summary>
        <remarks>
            アプリのすべての推奨事項オプトアウトの設定をリセットします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersForWebAppAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
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