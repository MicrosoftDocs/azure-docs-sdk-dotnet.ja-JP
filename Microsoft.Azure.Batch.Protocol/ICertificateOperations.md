<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Batch.Protocol.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            CertificateOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;" Usage="iCertificateOperations.AddWithHttpMessagesAsync (certificate, certificateAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificate">
            追加する証明書。
            </param>
        <param name="certificateAddOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントに証明書を追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.CancelDeletionWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelDeletionWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt;" Usage="iCertificateOperations.CancelDeletionWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除されている証明書の拇印です。
            </param>
        <param name="certificateCancelDeletionOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントからの証明書の削除に失敗をキャンセルします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。 証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。 証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。 証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.DeleteWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除する証明書の拇印です。
            </param>
        <param name="certificateDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントから証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。 証明書を削除することができます、前にする必要がありますので、証明書に関連付けられていない既存のプールのコンピューティング ノードであっても、プールから証明書を削除する場合は削除されません、プール内の既存のコンピューティング ノードから再起動するまで)、証明書がインストールされていないことを確認して、証明書の実行中のタスクが依存していません。 使用されている証明書を削除しようとすると、削除は失敗します。 証明書の状態は、deleteFailed に変更します。 取り消す証明書の削除を使用して、証明書の使用を続行することを決定する場合にアクティブな状態を設定することができます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate,Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt;" Usage="iCertificateOperations.GetWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate,Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            取得する証明書の拇印です。
            </param>
        <param name="certificateGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, class Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" Usage="iCertificateOperations.ListNextWithHttpMessagesAsync (nextPageLink, certificateListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="certificateListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, class Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" Usage="iCertificateOperations.ListWithHttpMessagesAsync (certificateListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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