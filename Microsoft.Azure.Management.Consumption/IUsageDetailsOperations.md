<Type Name="IUsageDetailsOperations" FullName="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IUsageDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageDetailsOperations" />
  <TypeSignature Language="F#" Value="type IUsageDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            UsageDetailsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync (string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync(string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListWithHttpMessagesAsync (scope, expand, filter, skiptoken, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
            Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。 前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。
            </param>
        <param name="top">
            最新の N usageDetails する結果の数を制限するために使用可能性があります。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            請求期間使用して、スコープの使用方法の詳細を示します。 使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>