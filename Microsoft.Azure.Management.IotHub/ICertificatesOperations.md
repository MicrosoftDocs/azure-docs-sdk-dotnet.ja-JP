<Type Name="ICertificatesOperations" FullName="Microsoft.Azure.Management.IotHub.ICertificatesOperations">
  <TypeSignature Language="C#" Value="public interface ICertificatesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificatesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.ICertificatesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificatesOperations" />
  <TypeSignature Language="F#" Value="type ICertificatesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            CertificatesOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="certificateDescription">
            証明書の本文。
            </param>
        <param name="ifMatch">
            証明書の ETag です。 新しい証明書を作成するのには指定しません。 既存の証明書の更新に必要です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            IoT hub を証明書をアップロードします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            新規に追加するか、既存の証明書を置き換えます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCertificatesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="ifMatch">
            証明書の ETag です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除、X509 証明書。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            削除、既存 X509 証明書またはが存在しない場合、何も行われません。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateVerificationCodeWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;" Usage="iCertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="ifMatch">
            証明書の ETag です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            所有しているフローの証拠の確認コードを生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            所有しているフローの証拠の確認コードを生成します。 検証コードを使用して、リーフ証明書を生成するされます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.GetWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            証明書を返します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
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
    <Member MemberName="ListByIotHubWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.ListByIotHubWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByIotHubWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;" Usage="iCertificatesOperations.ListByIotHubWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            証明書の一覧を返します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
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
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.VerifyWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            IoT ハブが含まれているリソース グループの名前。
            </param>
        <param name="resourceName">
            IoT hub の名前。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="certificateVerificationBody">
            証明書の名前
            </param>
        <param name="ifMatch">
            証明書の ETag です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の秘密キーを所有していることを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            確認のアップロード前証明書によって発行されたリーフ証明書を提供することによって、証明書の秘密キーを所有しているを確認します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
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