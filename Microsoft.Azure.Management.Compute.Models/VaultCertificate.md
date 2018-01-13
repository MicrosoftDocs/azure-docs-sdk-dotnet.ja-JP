<Type Name="VaultCertificate" FullName="Microsoft.Azure.Management.Compute.Models.VaultCertificate">
  <TypeSignature Language="C#" Value="public class VaultCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultCertificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VaultCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultCertificate" />
  <TypeSignature Language="F#" Value="type VaultCertificate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key Vault に単一の証明書参照を記述し、VM に証明書がある必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VaultCertificate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate (string certificateUrl = null, string certificateStore = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificateUrl, string certificateStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificateUrl As String = null, Optional certificateStore As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VaultCertificate : string * string -&gt; Microsoft.Azure.Management.Compute.Models.VaultCertificate" Usage="new Microsoft.Azure.Management.Compute.Models.VaultCertificate (certificateUrl, certificateStore)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateUrl" Type="System.String" />
        <Parameter Name="certificateStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateUrl">これは、シークレットとして Key Vault にアップロードされている証明書の URL です。 参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。
            証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64 でエンコードされた証明&gt;"、&lt;br&gt; "dataType":"pfx"&lt;br&gt; "password":"&lt;pfx ファイル パスワード&gt;"&lt;br&gt;}</param>
        <param name="certificateStore">Windows vm の場合は、証明書の追加先となる仮想マシンで、証明書ストアを指定します。 指定された証明書ストアは、LocalMachine アカウントでは暗黙的にします。 &lt;ブラジル&gt;&lt;br&gt;Linux Vm の場合は、証明書ファイルがディレクトリに配置/var/lib/waagent、ファイル名を持つ&lt;UppercaseThumbprint&gt;.crt の X509 証明書のファイルと&lt;UppercaseThumbpring&gt;.prv 秘密キーにします。 これらのファイルの両方が、.pem 形式です。</param>
        <summary>
            VaultCertificate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateStore">
      <MemberSignature Language="C#" Value="public string CertificateStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateStore As String" />
      <MemberSignature Language="F#" Value="member this.CertificateStore : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、または Windows vm の設定、証明書の追加先となる仮想マシンで、証明書ストアを指定します。 指定された証明書ストアは、LocalMachine アカウントでは暗黙的にします。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Linux vm の場合は、証明書ファイルがディレクトリに配置/var/lib/waagent、ファイル名を持つ&amp;lt;UppercaseThumbprint&amp;gt;。crt の X509 証明書ファイルと&amp;lt;UppercaseThumbpring&amp;gt;。秘密キーの prv です。 これらのファイルの両方が、.pem 形式です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、シークレットとして Key Vault にアップロードされている証明書の URL になります。 参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。
            証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;{&amp;lt; br&amp;gt;"data":"&amp;lt;Base64 でエンコードされた証明&amp;gt;"、&amp;lt; br&amp;gt;"dataType":"pfx"&amp;lt; br&amp;gt;"password":"&amp;lt; pfx ファイル パスワード&amp;gt;"&amp;lt; br&amp;gt;}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>