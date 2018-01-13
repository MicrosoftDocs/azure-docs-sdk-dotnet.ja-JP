<Type Name="IKey" FullName="Microsoft.Azure.KeyVault.Core.IKey">
  <TypeSignature Language="C#" Value="public interface IKey : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKey implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Core.IKey" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKey&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IKey = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            キーのためのインターフェイスします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; DecryptAsync (byte[] ciphertext, byte[] iv, byte[] authenticationData, byte[] authenticationTag, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; DecryptAsync(unsigned int8[] ciphertext, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.DecryptAsync(System.Byte[],System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptAsync (ciphertext As Byte(), iv As Byte(), authenticationData As Byte(), authenticationTag As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member DecryptAsync : byte[] * byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.DecryptAsync (ciphertext, iv, authenticationData, authenticationTag, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ciphertext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="authenticationTag" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="ciphertext">暗号化を解除する暗号テキスト</param>
        <param name="iv">初期化ベクター</param>
        <param name="authenticationData">認証データは、</param>
        <param name="authenticationTag">To be added.</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定した暗号テキストを復号化します。
            </summary>
        <returns>プレーン テキスト</returns>
        <remarks>アルゴリズムが指定されていない場合、実装では、既定のアルゴリズムを使用してください。
            すべてのアルゴリズムは、要求、またはすべてのパラメーターをサポートします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultEncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultEncryptionAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultEncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultEncryptionAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultEncryptionAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このキーの既定の暗号化アルゴリズム
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKeyWrapAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultKeyWrapAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultKeyWrapAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKeyWrapAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定のキーは、このキーのアルゴリズムを折り返す
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSignatureAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultSignatureAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSignatureAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSignatureAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSignatureAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このキーの既定の署名アルゴリズム
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],byte[],string&gt;&gt; EncryptAsync (byte[] plaintext, byte[] iv, byte[] authenticationData, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`3&lt;unsigned int8[], unsigned int8[], string&gt;&gt; EncryptAsync(unsigned int8[] plaintext, unsigned int8[] iv, unsigned int8[] authenticationData, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.EncryptAsync(System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function EncryptAsync (plaintext As Byte(), iv As Byte(), authenticationData As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member EncryptAsync : byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * byte[] * string&gt;" Usage="iKey.EncryptAsync (plaintext, iv, authenticationData, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plaintext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="plaintext">プレーン テキストを暗号化するには</param>
        <param name="iv">初期化ベクター</param>
        <param name="authenticationData">認証データは、</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定されたプレーン テキストを暗号化します。
            </summary>
        <returns>暗号化テキスト、認証タグ (該当する場合)、使用するアルゴリズムで構成されるタプル</returns>
        <remarks>アルゴリズムが指定されていない場合、実装では、既定のアルゴリズムを使用してください。
            すべて algorithyms が必要なまたはすべてのパラメーターをサポートします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キー識別子
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; SignAsync (byte[] digest, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; SignAsync(unsigned int8[] digest, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.SignAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function SignAsync (digest As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member SignAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.SignAsync (digest, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest">署名するダイジェスト</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定したダイジェストに署名します。
            </summary>
        <returns>署名と使用するアルゴリズムで構成されるタプル</returns>
        <remarks>実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; UnwrapKeyAsync (byte[] encryptedKey, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; UnwrapKeyAsync(unsigned int8[] encryptedKey, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.UnwrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnwrapKeyAsync (encryptedKey As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.UnwrapKeyAsync (encryptedKey, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptedKey" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encryptedKey">暗号化されたキー マテリアル</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定されたキー マテリアルを復号化します。
            </summary>
        <returns>復号化されたキー マテリアル</returns>
        <remarks>実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (byte[] digest, byte[] signature, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(unsigned int8[] digest, unsigned int8[] signature, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.VerifyAsync(System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function VerifyAsync (digest As Byte(), signature As Byte(), algorithm As String, token As CancellationToken) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member VerifyAsync : byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iKey.VerifyAsync (digest, signature, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest">ダイジェスト</param>
        <param name="signature">署名の値</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定された署名値を確認します。
            </summary>
        <returns>署名の確認に成功したかどうかを示すブール値</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; WrapKeyAsync (byte[] key, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; WrapKeyAsync(unsigned int8[] key, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.WrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function WrapKeyAsync (key As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.WrapKeyAsync (key, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key">暗号化キー マテリアル</param>
        <param name="algorithm">使用するアルゴリズム</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            指定されたキー マテリアルを暗号化します。
            </summary>
        <returns>暗号化されたキーと使用するアルゴリズムで構成されるタプル</returns>
        <remarks>実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</remarks>
      </Docs>
    </Member>
  </Members>
</Type>