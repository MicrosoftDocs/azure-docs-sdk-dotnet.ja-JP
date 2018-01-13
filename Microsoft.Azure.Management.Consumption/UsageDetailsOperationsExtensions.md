<Type Name="UsageDetailsOperationsExtensions" FullName="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageDetailsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            UsageDetailsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; List (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; List(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.List(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IUsageDetailsOperations, scope As String, Optional expand As String = null, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of UsageDetail)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.List (operations, scope, expand, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            使用方法の詳細のスコープです。 スコープは、'/サブスクリプション/{subscriptionid} ' サブスクリプションの場合または '/subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}' の課金 perdiod です。
            </param>
        <param name="expand">
            プロパティ/additionalProperties またはプロパティ/meterDetails 内での使用方法の詳細の一覧を展開して使用できます。 既定では、使用方法の詳細を一覧表示するときにこれらのフィールドは含まれません。
            </param>
        <param name="filter">
            可能性があります usageDetails をフィルター処理するまたはで使用プロパティ/usageEnd (Utc 時間)、(Utc 時間) のプロパティ/usageStart、/リソース グループのプロパティ、プロパティ/instanceName プロパティ/instanceId。 フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。 これはサポートされていません"ne"'または' または 'not' です。
            </param>
        <param name="skiptoken">
            Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。
            前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。
            </param>
        <param name="top">
            最新の N usageDetails する結果の数を制限するために使用可能性があります。
            </param>
        <summary>
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListAsync (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListAsync(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListAsync (operations, scope, expand, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            使用方法の詳細のスコープです。 スコープは、'/サブスクリプション/{subscriptionid} ' サブスクリプションの場合または '/subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}' の課金 perdiod です。
            </param>
        <param name="expand">
            プロパティ/additionalProperties またはプロパティ/meterDetails 内での使用方法の詳細の一覧を展開して使用できます。 既定では、使用方法の詳細を一覧表示するときにこれらのフィールドは含まれません。
            </param>
        <param name="filter">
            可能性があります usageDetails をフィルター処理するまたはで使用プロパティ/usageEnd (Utc 時間)、(Utc 時間) のプロパティ/usageStart、/リソース グループのプロパティ、プロパティ/instanceName プロパティ/instanceId。 フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。 これはサポートされていません"ne"'または' または 'not' です。
            </param>
        <param name="skiptoken">
            Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。
            前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。
            </param>
        <param name="top">
            最新の N usageDetails する結果の数を制限するために使用可能性があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; ListNext (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; ListNext(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNext(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IUsageDetailsOperations, nextPageLink As String) As IPage(Of UsageDetail)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
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
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
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
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>