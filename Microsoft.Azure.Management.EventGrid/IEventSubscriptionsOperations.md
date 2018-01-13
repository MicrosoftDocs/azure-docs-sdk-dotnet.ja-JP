<Type Name="IEventSubscriptionsOperations" FullName="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations">
  <TypeSignature Language="C#" Value="public interface IEventSubscriptionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventSubscriptionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventSubscriptionsOperations" />
  <TypeSignature Language="F#" Value="type IEventSubscriptionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            EventSubscriptionsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginCreateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginCreateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.BeginCreateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションを作成する必要とするリソースのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。 たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションを作成するの名前です。 イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。
            </param>
        <param name="eventSubscriptionInfo">
            移行先とフィルター情報を含むイベント サブスクリプションのプロパティ
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。 既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。
            </remarks>
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
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEventSubscriptionsOperations.BeginDeleteWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のイベント サブスクリプションを削除します。
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginUpdateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginUpdateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.BeginUpdateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            既存のイベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションを作成するの名前
            </param>
        <param name="eventSubscriptionUpdateParameters">
            サブスクリプションの更新されたイベント情報
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のイベント サブスクリプションを非同期に更新します。
            </remarks>
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
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; CreateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; CreateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.CreateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションを作成する必要とするリソースのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。 たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションを作成するの名前です。 イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。
            </param>
        <param name="eventSubscriptionInfo">
            移行先とフィルター情報を含むイベント サブスクリプションのプロパティ
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。 既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。
            </remarks>
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEventSubscriptionsOperations.DeleteWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のイベント サブスクリプションを削除します。
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt; GetFullUrlWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt; GetFullUrlWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.GetFullUrlWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFullUrlWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt;" Usage="iEventSubscriptionsOperations.GetFullUrlWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションの完全な URL を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            イベント サブスクリプションの完全なエンドポイント URL を取得します。
            </remarks>
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; GetWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; GetWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.GetWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            イベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            イベント サブスクリプションのプロパティを取得します。
            </remarks>
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
    <Member MemberName="ListByResourceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListByResourceWithHttpMessagesAsync (string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListByResourceWithHttpMessagesAsync(string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListByResourceWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListByResourceWithHttpMessagesAsync (resourceGroupName, providerNamespace, resourceTypeName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="providerNamespace">
            トピックのプロバイダーの Namespace
            </param>
        <param name="resourceTypeName">
            リソースの種類の名前
            </param>
        <param name="resourceName">
            リソースの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のトピックのすべてのイベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定のトピック用に作成されたすべてのイベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync (string resourceGroupName, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync(string resourceGroupName, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync (resourceGroupName, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="topicTypeName">
            トピックの種類の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定のトピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListGlobalByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure のサブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定の Azure サブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync (string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync(string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync (topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="topicTypeName">
            トピックの種類の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックの種類のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            トピックの種類の Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListGlobalBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalBySubscriptionWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalBySubscriptionWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalBySubscriptionWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションの集計の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定の Azure サブスクリプションの下のすべての集計のグローバル イベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync (string resourceGroupName, string location, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync(string resourceGroupName, string location, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync (resourceGroupName, location, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="location">
            場所の名前
            </param>
        <param name="topicTypeName">
            トピックの種類の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックの種類の Azure サブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定 Azure サブスクリプションとリソース グループとトピックの種類の下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListRegionalByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupWithHttpMessagesAsync (string resourceGroupName, string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupWithHttpMessagesAsync(string resourceGroupName, string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalByResourceGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalByResourceGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalByResourceGroupWithHttpMessagesAsync (resourceGroupName, location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            ユーザーのサブスクリプション内のリソース グループの名前。
            </param>
        <param name="location">
            場所の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure のサブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定の Azure サブスクリプションとリソース グループの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync (string location, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync(string location, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync (location, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            場所の名前
            </param>
        <param name="topicTypeName">
            トピックの種類の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            トピックの種類の Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定の Azure サブスクリプションとトピック種類の指定した場所からのすべてのイベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="ListRegionalBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionWithHttpMessagesAsync (string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionWithHttpMessagesAsync(string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalBySubscriptionWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalBySubscriptionWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalBySubscriptionWithHttpMessagesAsync (location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            場所の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            特定の Azure サブスクリプションの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。
            </remarks>
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
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; UpdateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; UpdateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.UpdateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            既存のイベント サブスクリプションのスコープです。 スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。
            たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。
            </param>
        <param name="eventSubscriptionName">
            イベント サブスクリプションを作成するの名前
            </param>
        <param name="eventSubscriptionUpdateParameters">
            サブスクリプションの更新されたイベント情報
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            イベント サブスクリプションを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存のイベント サブスクリプションを非同期に更新します。
            </remarks>
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