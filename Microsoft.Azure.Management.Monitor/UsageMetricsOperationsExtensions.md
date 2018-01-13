<Type Name="UsageMetricsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageMetricsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageMetricsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageMetricsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageMetricsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            UsageMetricsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; List (this Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; List(class Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IUsageMetricsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IUsageMetricsOperations, resourceUri As String, apiVersion As String, Optional odataQuery As ODataQuery(Of UsageMetric) = null) As IEnumerable(Of UsageMetric)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IUsageMetricsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" Usage="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.List (operations, resourceUri, apiVersion, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceUri">
            リソースの識別子。
            </param>
        <param name="apiVersion">
            クライアント Api のバージョン。 注: このプロパティではありません、クライアントの呼び出しで明示的な場合があります、既定値はありません。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            一覧操作では、リソースの使用状況メトリックが一覧表示します。&lt;br&gt;**警告**: この操作になります*廃止*次のリリースでします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IUsageMetricsOperations operations, string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IUsageMetricsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IUsageMetricsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions.ListAsync (operations, resourceUri, apiVersion, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.UsageMetricsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceUri">
            リソースの識別子。
            </param>
        <param name="apiVersion">
            クライアント Api のバージョン。 注: このプロパティではありません、クライアントの呼び出しで明示的な場合があります、既定値はありません。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            一覧操作では、リソースの使用状況メトリックが一覧表示します。&lt;br&gt;**警告**: この操作になります*廃止*次のリリースでします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>