<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Management.Automation.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            オートメーションの証明書をサービス操作。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;" Usage="iCertificateOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="parameters">
            証明書の作成または更新の操作に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書を作成します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            証明書の作成または更新の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.DeleteAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書を削除します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;" Usage="iCertificateOperations.GetAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の名前によって識別される証明書を取得します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            証明書の取得操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            一覧の証明書の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次の項目のセットを取得するリンクです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の [次へ] の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            一覧の証明書の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="parameters">
            証明書の更新プログラムの操作に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書を更新します。  (詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>