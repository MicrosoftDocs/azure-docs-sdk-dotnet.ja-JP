<Type Name="KeyVaultClientExtensions" FullName="Microsoft.Azure.KeyVault.KeyVaultClientExtensions">
  <TypeSignature Language="C#" Value="public static class KeyVaultClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit KeyVaultClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module KeyVaultClientExtensions" />
  <TypeSignature Language="F#" Value="type KeyVaultClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            KeyVaultClient の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupKeyAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーのバックアップをクライアントにダウンロードするように要求します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーのバックアップ操作は、保護された形式で、Azure Key Vault からキーをエクスポートします。 この操作では、Azure Key Vault システムの外部で使用できる形式では、キー マテリアルは返しません、返されるキー マテリアルは保護 Azure Key Vault HSM または Azure Key Vault 自体ことに注意してください。
            この操作の目的は、キーのバックアップ、1 つの Azure Key Vault インスタンスでキーを生成し、別の Azure Key Vault インスタンスに復元してクライアントを許可するのにです。 バックアップ操作は、エクスポートする保護対象のフォームでは、Azure Key Vault からのすべてのキー タイプに使用可能性があります。 キーの個別のバージョンは、バックアップすることはできません。 バックアップ/復元は地理的な境界のみ; 内で実行できます別の地理的領域に 1 つの地理的領域からバックアップを復元できないことを意味します。 たとえば、米国の地理的領域からのバックアップを EU の地理的領域に復元できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupSecretAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したシークレットのバックアップをクライアントにダウンロードするように要求します。
            認証:、シークレット/バックアップ権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateCertificateAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これが最初のバージョンである場合は、証明書リソースが作成されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.NewKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.NewKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.KeyVault.Models.NewKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            新しいキーの名前です。 システムでは、新しいキーのバージョン名を生成します。
            </param>
        <param name="kty">
            作成するキーの型。 有効な値は、JsonWebKeyType を参照してください。 使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'
            </param>
        <param name="keySize">
            キーのサイズ (バイト単位)。 たとえば、1024 または 2048。
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいキーを作成、格納、キー パラメーターを返し、属性をクライアントにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの作成処理は、Azure Key Vault 内のすべてのキー タイプの作成に使用できます。 名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] cipherText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] cipherText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, keyIdentifier, algorithm, cipherText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="cipherText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier">完全なキー識別子</param>
        <param name="algorithm">アルゴリズム。 可能なアルゴリズムの種類の詳細については、JsonWebKeyEncryptionAlgorithm を参照してください。</param>
        <param name="cipherText">暗号化テキスト</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            暗号化されたデータの 1 つのブロックを復号化します。
            </summary>
        <returns>復号化の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            暗号化されたデータの 1 つのブロックを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            DECRYPT 操作は、ターゲット暗号化キーと指定されたアルゴリズムを使用して暗号テキストの整形式ブロックを解除します。 この操作は、ENCRYPT 操作の逆だけでデータの 1 つのブロックは、暗号化が解除された可能性があります、このブロックのサイズは対象のキーと使用するアルゴリズムによって異なります。 DECRYPT 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーから証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            関連付けられているポリシーと共に証明書オブジェクトのすべてのバージョンを削除します。 削除証明書オブジェクトの個々 のバージョンを削除する証明書を使用することはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateContactsAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の連絡先を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定した資格情報コンテナー証明書の証明書の連絡先を削除します。
            認証:、証明書/managecontacts 権限が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateIssuerAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            DeleteCertificateIssuer 操作は、資格情報コンテナーから、指定された証明書の発行者を完全に削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateOperationAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の操作を削除します。 認証:、証明書/更新アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteKeyAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            削除するキーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Key Vault に記憶域から任意の型のキーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの個別のバージョンを削除するキーの削除操作を使用できません。 この操作は、キーが署名/検証、ラップ/ラップ解除または暗号化/暗号化解除操作に使用しないことを意味すると、キーに関連付けられている暗号化マテリアルを削除します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSasDefinitionAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントから SAS 定義を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSecretAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault からシークレットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            削除操作は、Azure Key Vault に格納されているシークレットに適用されます。
            削除は、個々 のバージョンのシークレットに適用できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteStorageAccountAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストレージ アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] plainText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] plainText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, keyIdentifier, algorithm, plainText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="plainText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier">完全なキー識別子</param>
        <param name="algorithm">アルゴリズム。 可能なアルゴリズムの種類の詳細については、JsonWebKeyEncryptionAlgorithm を参照してください。</param>
        <param name="plainText">プレーン テキスト</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            データの 1 つのブロックを暗号化します。 暗号化することがありますのあるデータの量は、対象キーの種類と暗号化アルゴリズムによって決まります。
            </summary>
        <returns>暗号化されたテキスト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Key vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ENCRYPT 操作では、Azure Key Vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。 暗号化操作はサイズが、対象のキーと使用する暗号化アルゴリズムに依存して、データの 1 つのブロックのみをサポートする注意してください。 暗号化操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。 この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, certificateIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier">証明書の URL です。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            証明書を取得します。
            </summary>
        <returns>取得した証明書</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">証明書を含む資格情報コンテナーの URL です。</param>
        <param name="certificateName">指定された資格情報コンテナー内の証明書の名前。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            証明書を取得します。
            </summary>
        <returns>取得した証明書</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定された資格情報コンテナー内の証明書の名前。
            </param>
        <param name="certificateVersion">
            証明書のバージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関する情報を取得します。 認証:、証明書/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateContactsAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の連絡先の一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateContacts 操作は、指定されたキー コンテナーに証明書の連絡先のリソースのセットを返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuerAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者の一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuer 操作は、指定されたキー コンテナーに指定された証明書発行者リソースを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の発行者をリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定されたキー コンテナーの証明書の発行者をリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateOperationAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関連付けられている操作を取得します。 認証:、証明書/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatePolicyAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定されたキー コンテナーに証明書の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のポリシーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificatePolicy 操作は、指定されたキー コンテナーに指定された証明書ポリシー リソースを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーに証明書の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesNextAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定されたキー コンテナーに証明書の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync (operations, vaultBaseUrl, certificateName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsNextAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            証明書のバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificateAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された削除済み証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificate 操作は、削除された証明書の情報と保有期間、スケジュールされた永続的な削除、および現在の回復レベルでの削除など、その属性を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeyAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キーの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除済みのキー情報とその属性を取得します。 認証:、キー/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーをリストが削除されました。 認証:、キー/一覧表示権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysNextAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定した資格情報コンテナー内のキーをリストが削除されました。 認証:、キー/一覧表示権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除された秘密情報とその属性を取得します。
            認証:、シークレット/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーに削除された機密情報を一覧表示します。 認証:、シークレット/リスト権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定した資格情報コンテナーに削除された機密情報を一覧表示します。 認証:、シークレット/リスト権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, keyIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier">キー識別子</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            キーとその属性の公開部分を取得します
            </summary>
        <returns>キーとその属性の KeyBundle</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">資格情報コンテナー名、https://myvault.vault.azure.net 例:</param>
        <param name="keyName">キー名</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            キーとその属性の公開部分を取得します
            </summary>
        <returns>キーとその属性の KeyBundle</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            取得するキーの名前。
            </param>
        <param name="keyVersion">
            バージョン パラメーターを追加するには、特定のバージョンのキーを取得します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            格納されているキーのパブリックの部分を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの取得操作は、すべてのキー タイプに適用できます。 要求されたキーが対称の場合は、し、キー マテリアルではリリースされません応答します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。 LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。 キーの個別のバージョンは、応答には表示されません。 認証:、キー/一覧表示権限が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定した資格情報コンテナー内のキーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。 LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。 キーの個別のバージョンは、応答には表示されません。 認証:、キー/一覧表示権限が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync (operations, vaultBaseUrl, keyName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            同じキー名で個別キー バージョンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            完全なキー識別子、属性、およびタグは、応答で提供されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsNextAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            同じキー名で個別キー バージョンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            完全なキー識別子、属性、およびタグは、応答で提供されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetPendingCertificateSigningRequestAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetPendingCertificateSigningRequestAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPendingCertificateSigningRequestAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetPendingCertificateSigningRequestAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">証明書を含む資格情報コンテナーの URL</param>
        <param name="certificateName">証明書の名前</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            保留中の証明書署名要求 (10 PKCS)、Base64 を取得します。 
            </summary>
        <returns>保留中の証明書署名要求を Base64 としてエンコードされた文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの SAS の定義に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync (operations, vaultBaseUrl, storageAccountName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, secretIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier">シークレットの URL です。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            シークレットを取得します。
            </summary>
        <returns>シークレットを含む応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">シークレットを含む資格情報コンテナーの URL です。</param>
        <param name="secretName">指定された資格情報コンテナーに機密情報の名前です。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            シークレットを取得します。
            </summary>
        <returns>シークレットを含む応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="secretVersion">
            シークレットのバージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーから、指定されたシークレットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GET 操作は、Azure Key Vault に格納されているシークレットに適用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault にシークレットの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。 個別のシークレット バージョンは、応答には表示されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定された key vault にシークレットの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。 個別のシークレット バージョンは、応答には表示されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync (operations, vaultBaseUrl, secretName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したシークレットのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。 完全なシークレット識別子および属性は、応答で提供されます。 シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsNextAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定したシークレットのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。 完全なシークレット識別子および属性は、応答で提供されます。 シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsNextAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
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
            指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, certificateCollection, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateCollection" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">証明書を含む資格情報コンテナーの URL</param>
        <param name="certificateName">証明書の名前</param>
        <param name="certificateCollection">秘密キーで証明書のコレクション</param>
        <param name="certificatePolicy">証明書の管理ポリシー</param>
        <param name="certificateAttributes">(省略可能) の証明書の属性</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            証明書の新しいバージョンをインポートします。 これが最初のバージョンである場合は、証明書リソースが作成されます。
            </summary>
        <returns>資格情報コンテナーに証明書のバンドルをインポートします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="base64EncodedCertificate">
            インポートする証明書オブジェクトの表現を Base64 にエンコードされます。 この証明書を秘密キーを含める必要があります。
            </param>
        <param name="password">
            Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーに証明書をインポートします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存有効な証明書を Azure Key Vault には秘密キーを含むをインポートします。 インポートする証明書は、PFX または PEM のいずれかの形式であることができます。 キーだけでなく x509 PEM ファイルを含める必要があります PEM 形式での証明書がある場合の証明書。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, Nullable&lt;bool&gt; importToHardware = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, valuetype System.Nullable`1&lt;bool&gt; importToHardware, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.KeyBundle,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.KeyBundle * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, keyBundle, importToHardware, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyBundle" Type="Microsoft.Azure.KeyVault.Models.KeyBundle" />
        <Parameter Name="importToHardware" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">資格情報コンテナー名、https://myvault.vault.azure.net 例:</param>
        <param name="keyName">キー名</param>
        <param name="keyBundle"> キーのバンドル </param>
        <param name="importToHardware">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか </param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            指定した資格情報コンテナーにキーをインポートします。
            </summary>
        <returns> 資格情報コンテナーにキーのバンドルをインポート </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            インポートしたキーの名前です。
            </param>
        <param name="key">
            Json web key
            </param>
        <param name="hsm">
            ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。
            </param>
        <param name="keyAttributes">
            キー管理の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            外部で作成されたキーをインポートする格納し、キー パラメーターを返し、属性をクライアントにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            インポート キー操作は、すべてのキー タイプを Azure Key Vault にインポートするために使用可能性があります。 名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="x509Certificates">
            証明書または証明書チェーンをマージします。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            MergeCertificate 操作では、証明書またはサービスで現在使用できるキーのペアで証明書チェーンのマージを実行します。
            認証:、証明書/更新アクセス許可が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">証明書を含む資格情報コンテナーの URL</param>
        <param name="certificateName">証明書の名前</param>
        <param name="x509Certificates">証明書またはマージする certificte チェーン</param>
        <param name="certificateAttributes">(省略可能) の証明書の属性</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。
            </summary>
        <returns>マージされた証明書を含む応答メッセージです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除から返された、削除された証明書の recoveryId します。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            すぐに削除された証明書を削除します。
            </summary>
        <returns>この要求の非同期実行を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された削除済み証明書を完全に削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            PurgeDeletedCertificate 操作では、指定された証明書を回復する可能性の元に戻すことの削除を実行します。 操作は回復レベルで 'Purgeable' が指定されていない場合に使用できません。
            明示的な '削除' 権限を許可する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除から削除された、キーの recoveryId が返されます。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            すぐに削除されたキーを削除します。
            </summary>
        <returns>この要求の非同期実行を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キーの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを完全に削除します。 別名、キーを削除します。 認証:、キー/削除アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除されないように、削除されたシークレットの recoveryId が返されます。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            すぐに削除されたシークレットを削除します。
            </summary>
        <returns>この要求の非同期実行を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたシークレットを完全に削除します。 別名、シークレットを削除します。
            認証:、シークレット/削除アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除から返された、削除された証明書の recoveryId します。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            削除済みの証明書を回復します。
            </summary>
        <returns>回復された証明書を格納した応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            削除済みの証明書の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のバージョンに戻す、削除された証明書を回復します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            RecoverDeletedCertificate 操作では、削除操作の取り消しを実行します。 操作は、ソフト削除の有効な資格情報コンテナーに適用し、間隔、保有期間 (削除済み証明書の属性で使用可能) 発行する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除から削除された、キーの recoveryId が返されます。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            削除されたキーを回復します。
            </summary>
        <returns>回復キーを含む応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            削除されたキーの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除されたキーに戻します/keys 下にある現在のバージョンを回復します。
            認証:、キー/回復のアクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId">削除されないように、削除されたシークレットの recoveryId が返されます。</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            削除されたシークレットを復元します。
            </summary>
        <returns>回復されたシークレットを含む応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            削除されたシークレットの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            /Secrets 下にある現在のバージョンに削除されたシークレット バックアップを復元します。
            認証:、シークレット/回復のアクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateStorageAccountKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync (operations, vaultBaseUrl, storageAccountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RegenerateStorageAccountKeyAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="keyName">
            ストレージ アカウント キーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの指定したキー値を再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] keyBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] keyBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync (operations, vaultBaseUrl, keyBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreKeyAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyBundleBackup">
            キーのバンドルに関連付けられているバックアップ blob です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            資格情報コンテナーにキーをバックアップを復元します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure Key Vault、キー、そのキー識別子、属性、およびアクセス制御ポリシーを復元するのには、以前にバックアップ キーをインポートします。 復元操作は、以前にバックアップ キーをインポートするために使用可能性があります。 キーの個別のバージョンを復元することはできません。 キーにはバックアップ時と同じキー名で全体として復元されます。 キー名をターゲット Key Vault では使用できない場合、復元操作は拒否されます。 キー名は、復元中に保持されますが、中に、最終的なキー識別子は、別の資格情報コンテナーにキーを復元した場合に変更されます。 復元では、すべてのバージョンを復元し、バージョン識別子を保持します。 復元操作のセキュリティの制約があります。 ターゲット Key Vault はソース Key Vault、ユーザーがターゲット Key Vault で復元権限を必要と同じ Microsoft Azure サブスクリプションで所有する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] secretBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] secretBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync (operations, vaultBaseUrl, secretBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreSecretAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretBundleBackup">
            シークレットのバンドルに関連付けられているバックアップ blob です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            資格情報コンテナーにシークレットをバックアップを復元します。 認証:、シークレット/復元権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.Contacts * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync (operations, vaultBaseUrl, contacts, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateContactsAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="contacts">
            キー コンテナーの証明書の連絡先。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーの証明書の連絡先を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したキー資格情報コンテナーの証明書の連絡先を設定します。 認証:、証明書/managecontacts 権限が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateIssuerAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="provider">
            発行元プロバイダー。
            </param>
        <param name="credentials">
            発行者のための資格情報。
            </param>
        <param name="organizationDetails">
            発行元に提供される組織の詳細です。
            </param>
        <param name="attributes">
            発行元のオブジェクトの属性。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            SetCertificateIssuer 操作を追加または指定された証明書の発行者を更新します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSasDefinitionAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="parameters">
            Sas 定義は、キー/値ペアの形式でのメタデータを作成します。
            </param>
        <param name="sasDefinitionAttributes">
            SAS の定義の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたストレージ アカウントに対して新しい SAS 定義を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync (operations, vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSecretAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="value">
            シークレットの値です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="contentType">
            パスワードなどの秘密の値の型。
            </param>
        <param name="secretAttributes">
            シークレットの管理の属性です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault のシークレットを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            設定操作では、Azure Key Vault にシークレットを追加します。 名前付きのシークレットが既に存在する場合、Azure Key Vault はシークレットの新しいバージョンを作成します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetStorageAccountAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="resourceId">
            ストレージ アカウントのリソース id です。
            </param>
        <param name="activeKeyName">
            現在アクティブなストレージ アカウント キーの名前。
            </param>
        <param name="autoRegenerateKey">
            かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。
            </param>
        <param name="regenerationPeriod">
            キーの生成 ISO 8601 形式で指定されている期間。
            </param>
        <param name="storageAccountAttributes">
            ストレージ アカウントの属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、新しいストレージ アカウントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, keyIdentifier, algorithm, digest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> 署名キーのグローバルのキー識別子 </param>
        <param name="algorithm">署名アルゴリズムです。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 </param>
        <param name="digest">署名するダイジェスト値</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            資格情報コンテナーで指定したキーを使用してダイジェストをから署名を作成します。
            </summary>
        <returns>署名の値</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            署名/検証アルゴリズムの識別子です。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用してダイジェストをから署名を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サインイン操作は、非対称キーおよび対称キーをこの操作は、キーの秘密部分を使用するために、Azure Key Vault に格納されているに適用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] wrappedKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] wrappedKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, keyIdentifier, algorithm, wrappedKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="wrappedKey" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> ラップ/ラップ解除キーのグローバルのキー識別子 </param>
        <param name="algorithm">Unwrap アルゴリズムです。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</param>
        <param name="wrappedKey">ラップされた対称キー</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            最初に、キー ラップに使用されている資格情報コンテナーに指定したキーを使用して対称キーのラップを解除します。
                </summary>
        <returns>ラップ解除された対称キー</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            そのキーをラップするために使用された最初に指定したキーを使用して対称キーのラップを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UNWRAP 操作は、対象キーの暗号化キーを使用して対称キーの復号化をサポートします。 この操作は、WRAP 操作の逆です。 UNWRAP 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, certificateIdentifier, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier">証明書の URL です。</param>
        <param name="certificatePolicy">証明書の管理ポリシー。</param>
        <param name="certificateAttributes">(省略可能) の証明書の属性</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            証明書のバージョンを更新します。
            </summary>
        <returns>更新された証明書。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定されたキー コンテナーに証明書の名前。
            </param>
        <param name="certificateVersion">
            証明書のバージョン。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の証明書に関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UpdateCertificate 操作は指定された証明書の指定した更新プログラムを適用します。要素だけが更新中は、証明書の属性に注意してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateIssuerAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="provider">
            発行元プロバイダー。
            </param>
        <param name="credentials">
            発行者のための資格情報。
            </param>
        <param name="organizationDetails">
            発行元に提供される組織の詳細です。
            </param>
        <param name="attributes">
            発行元のオブジェクトの属性。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UpdateCertificateIssuer 操作は、指定された証明書発行者のエンティティの更新プログラムを実行します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationRequested, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateOperationAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationRequested">
            証明書の操作のキャンセルが要求されたかどうかを示します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の操作を更新します。 認証:、証明書/更新アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificatePolicyAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定された資格情報コンテナー内の証明書の名前。
            </param>
        <param name="certificatePolicy">
            証明書のポリシーです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のポリシーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            証明書のポリシーで指定したメンバーを設定します。 Null として他のユーザーのままにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, keyIdentifier, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier">キー識別子</param>
        <param name="keyOps">Json web キー操作。 詳細については、JsonWebKeyOperation を参照してください。</param>
        <param name="attributes">キーの新しい属性。 キー属性の詳細については、KeyAttributes を参照してください。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            指定したキーに関連付けられているキー属性を更新します。
            </summary>
        <returns> 更新されたキー </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">資格情報コンテナー名、https://myvault.vault.azure.net 例:</param>
        <param name="keyName">キー名</param>
        <param name="keyOps">Json web キー操作。 考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。</param>
        <param name="attributes">キーの新しい属性。 キー属性の詳細については、KeyAttributes を参照してください。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            指定したキーに関連付けられているキー属性を更新します。
            </summary>
        <returns> 更新されたキー </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            更新するキーの名前。
            </param>
        <param name="keyVersion">
            更新するキーのバージョン。
            </param>
        <param name="keyOps">
            Json web キー操作。 考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            キー操作の変更の更新は、格納されたキーの属性を指定し、任意のキーの型と Azure Key Vault に格納されているキーのバージョンに適用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作を実行するために Key Vault にキーが既に存在しています。 注: キー自体の暗号化マテリアルは変更できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSasDefinitionAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="parameters">
            Sas の定義は、キー/値ペアの形式でメタデータを更新します。
            </param>
        <param name="sasDefinitionAttributes">
            SAS の定義の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の SAS 定義に関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, secretIdentifier, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier">シークレットの URL</param>
        <param name="contentType">パスワードなどの秘密の値の型。</param>
        <param name="secretAttributes">シークレットの属性。 使用可能な属性の詳細については、SecretAttributes を参照してください。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            指定されたシークレットに関連付けられている属性を更新します。
            </summary>
        <returns>更新されたシークレットを含む応答メッセージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="secretVersion">
            シークレットのバージョン。
            </param>
        <param name="contentType">
            パスワードなどの秘密の値の型。
            </param>
        <param name="secretAttributes">
            シークレットの管理の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーに指定されたシークレットを使用して関連付けられている属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            更新操作は、既存の格納されているシークレットの指定された属性を変更します。 要求で指定されていない属性のまま変更されません。 シークレット自体の値は変更できません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateStorageAccountAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="activeKeyName">
            現在アクティブなストレージ アカウント キー名。
            </param>
        <param name="autoRegenerateKey">
            かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。
            </param>
        <param name="regenerationPeriod">
            キーの生成 ISO 8601 形式で指定されている期間。
            </param>
        <param name="storageAccountAttributes">
            ストレージ アカウントの属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のストレージ アカウントに関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, keyIdentifier, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> 署名に使用されるキーのグローバルのキー識別子 </param>
        <param name="algorithm"> 署名/検証アルゴリズムです。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</param>
        <param name="digest"> 署名に使用されるダイジェスト </param>
        <param name="signature"> 検証対象の署名 </param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            指定したキーを使用して署名を検証します。
            </summary>
        <returns> 署名検証済みの場合は false、それ以外の場合は true。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            署名/検証アルゴリズムです。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'
            </param>
        <param name="digest">
            ダイジェストの署名に使用します。
            </param>
        <param name="signature">
            検証対象の署名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用して署名を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            検証処理は、Azure Key Vault に格納された対称キーを適用されます。 確認は不要な厳密にキーのパブリック部分を使用して署名の検証を実行できますが、この操作は、キー参照のみを持つ呼び出し元の便宜を図ってサポートので、Azure Key Vault に格納されている非対称キーのないと、キーのパブリックの部分です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] key, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] key, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, keyIdentifier, algorithm, key, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> 折り返しを使用するキーのグローバルのキー識別子 </param>
        <param name="algorithm"> ラップのアルゴリズム。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</param>
        <param name="key"> 対称キー </param>
        <param name="cancellationToken">省略可能なキャンセル トークン</param>
        <summary>
            指定したキーを使用して対称キーをラップします。
            </summary>
        <returns> ラップされた対称キー </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用して対称キーをラップします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            WRAP 操作では、以前、Azure Key Vault に格納されているキーの暗号化キーを使用して対称キーの暗号化をサポートします。 WRAP 操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。 この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>