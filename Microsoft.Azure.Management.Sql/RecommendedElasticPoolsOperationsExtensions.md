<Type Name="RecommendedElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendedElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool Get (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool Get(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String) As RecommendedElasticPool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.Get (operations, resourceGroupName, serverName, recommendedElasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            取得することをお勧め弾力性プールの名前。
            </param>
        <summary>
            推奨されるエラスティック プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; GetAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; GetAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
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
            サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            取得することをお勧め弾力性プールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            推奨されるエラスティック プールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; ListByServer (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; ListByServer(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of RecommendedElasticPool)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <summary>
            推奨されるエラスティック プールを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
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
            サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            推奨されるエラスティック プールを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; ListMetrics (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; ListMetrics(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetrics(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String) As IEnumerable(Of RecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetrics (operations, resourceGroupName, serverName, recommendedElasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            取得することをお勧め弾力性プールの名前。
            </param>
        <summary>
            推奨されるエラスティック プールのメトリックを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
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
            サーバーの名前。
            </param>
        <param name="recommendedElasticPoolName">
            取得することをお勧め弾力性プールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            推奨されるエラスティック プールのメトリックを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>