<Type Name="INameOperations" FullName="Microsoft.Azure.Management.NotificationHubs.INameOperations">
  <TypeSignature Language="C#" Value="public interface INameOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INameOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.INameOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface INameOperations" />
  <TypeSignature Language="F#" Value="type INameOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            NameOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt; CheckAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt; CheckAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INameOperations.CheckAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt;" Usage="iNameOperations.CheckAvailabilityWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            名前空間の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Azure サブスクリプション間、指定されたサービス名前空間の可用性を確認します。 これは、機能は、ドメイン名でサービス名前空間の名前に基づいて作成されるため便利です。
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