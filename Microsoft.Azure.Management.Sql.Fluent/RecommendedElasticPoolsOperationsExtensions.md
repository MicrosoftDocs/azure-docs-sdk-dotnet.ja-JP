<Type Name="RecommendedElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendedElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RecommendedElasticPoolsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            Azure SQL 推奨弾力性プールを取得するの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL 推奨エラスティック プールに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.GetDatabasesAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;GetDatabasesAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            取得するには、Azure SQL 弾力性プールの名前。
            </param>
        <param name="databaseName">
            取得する Azure SQL データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL 推奨弾力性プール内で Azure SQL データベースに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL 推奨の弾力性プールに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListDatabasesAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListDatabasesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            Azure SQL 推奨弾力性プールを取得するの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL 推奨弾力性プール内での Azure SQL データベースに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.RecommendedElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            Azure SQL 推奨弾力性プールを取得するの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            弾力性プールの推奨されるメトリックに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>