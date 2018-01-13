<Type Name="IRecordSetsOperations" FullName="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations">
  <TypeSignature Language="C#" Value="public interface IRecordSetsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecordSetsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecordSetsOperations" />
  <TypeSignature Language="F#" Value="type IRecordSetsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            RecordSetsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="relativeRecordSetName">
            レコードの名前は、ゾーンの名前に対して設定します。
            </param>
        <param name="recordType">
            このレコード セット内の DNS レコードの型。 レコード セットの種類が SOA を更新できますが、作成されません (作成、DNS ゾーンの作成時に)。 使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'
            </param>
        <param name="parameters">
            CreateOrUpdate 操作に渡されるパラメーター。
            </param>
        <param name="ifMatch">
            レコード セットの etag です。 常に、現在のレコード セットを上書きするには、この値を省略します。 変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' セットを記録が、既存の更新を防ぐために新しいレコードを作成するセットを許可します。 その他の値は無視されます。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはレコードの DNS ゾーン内で設定を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecordSetsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="relativeRecordSetName">
            レコードの名前は、ゾーンの名前に対して設定します。
            </param>
        <param name="recordType">
            このレコード セット内の DNS レコードの型。 SOA を削除することはできません型のセットを記録 (することで DNS ゾーンを削除したときに、削除されます)。
            使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'
            </param>
        <param name="ifMatch">
            レコード セットの etag です。 常に、現在のレコード セットを削除するには、この値を省略します。 誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            DNS ゾーンからレコードを削除します。 削除操作は元に戻すことができません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.GetWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="relativeRecordSetName">
            レコードの名前は、ゾーンの名前に対して設定します。
            </param>
        <param name="recordType">
            このレコード セット内の DNS レコードの型。 使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            レコード セットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="ListByDnsZoneNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
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
            DNS ゾーン内のすべてのレコード セットを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="ListByDnsZoneWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync (string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync (resourceGroupName, zoneName, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
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
            DNS ゾーン内の指定した種類のレコード セットを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="ListByTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync (string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByTypeWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeWithHttpMessagesAsync (resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="recordType">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="zoneName">
            (末尾のドット) なしの DNS ゾーンの名前。
            </param>
        <param name="relativeRecordSetName">
            レコードの名前は、ゾーンの名前に対して設定します。
            </param>
        <param name="recordType">
            このレコード セット内の DNS レコードの型。 使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'
            </param>
        <param name="parameters">
            更新操作に渡されるパラメーター。
            </param>
        <param name="ifMatch">
            レコード セットの etag です。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の etag 値を指定します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            レコードの DNS ゾーン内で設定を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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