<Type Name="SecurityProviderX509Certificate" FullName="Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate">
  <TypeSignature Language="C#" Value="public class SecurityProviderX509Certificate : Microsoft.Azure.Devices.Shared.SecurityProviderX509" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityProviderX509Certificate extends Microsoft.Azure.Devices.Shared.SecurityProviderX509" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityProviderX509Certificate&#xA;Inherits SecurityProviderX509" />
  <TypeSignature Language="F#" Value="type SecurityProviderX509Certificate = class&#xA;    inherit SecurityProviderX509" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Shared.SecurityProviderX509</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6238e-101">デバイスのセキュリティ クライアントの X509 証明書オブジェクトを使用して認証します。</span><span class="sxs-lookup"><span data-stu-id="6238e-101">The Device Security Client for X509 authentication using a certificate object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityProviderX509Certificate (System.Security.Cryptography.X509Certificates.X509Certificate2 clientCertificate, System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateChain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.X509Certificates.X509Certificate2 clientCertificate, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateChain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.#ctor(System.Security.Cryptography.X509Certificates.X509Certificate2,System.Security.Cryptography.X509Certificates.X509Certificate2Collection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientCertificate As X509Certificate2, Optional certificateChain As X509Certificate2Collection = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate : System.Security.Cryptography.X509Certificates.X509Certificate2 * System.Security.Cryptography.X509Certificates.X509Certificate2Collection -&gt; Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate" Usage="new Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate (clientCertificate, certificateChain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientCertificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
        <Parameter Name="certificateChain" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
      </Parameters>
      <Docs>
        <param name="clientCertificate"><span data-ttu-id="6238e-102">クライアント証明書の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="6238e-102">The client certificate used for authentication.</span></span></param>
        <param name="certificateChain"><span data-ttu-id="6238e-103">ルート証明書につながる証明書チェーンは、プロビジョニング サービスにアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="6238e-103">The certificate chain leading to the root certificate uploaded to the Provisioning service.</span></span></param>
        <summary>
            <span data-ttu-id="6238e-104">SecurityProviderX509Certificate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6238e-104">Initializes a new instance of the SecurityProviderX509Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="securityProviderX509Certificate.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="6238e-105">マネージ コードとアンマネージ リソースを解放する場合は truefalse には、アンマネージ リソースだけを解放します。</span><span class="sxs-lookup"><span data-stu-id="6238e-105">true to release both managed and unmanaged resources; false to releases only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="6238e-106">SecurityProviderX509Certificate によって使用されているアンマネージ リソースを解放し、必要に応じてマネージ リソースを破棄します。</span><span class="sxs-lookup"><span data-stu-id="6238e-106">Releases the unmanaged resources used by the SecurityProviderX509Certificate and optionally disposes of the managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificate">
      <MemberSignature Language="C#" Value="public override System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2 GetAuthenticationCertificate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.GetAuthenticationCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAuthenticationCertificate () As X509Certificate2" />
      <MemberSignature Language="F#" Value="override this.GetAuthenticationCertificate : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2" Usage="securityProviderX509Certificate.GetAuthenticationCertificate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6238e-107">サーバー側でインストールされている信頼されたルートで終了する証明書信頼チェーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="6238e-107">Gets the certificate trust chain that will end in the Trusted Root installed on the server side.</span></span>
            </summary>
        <returns><span data-ttu-id="6238e-108">証明書チェーン。</span><span class="sxs-lookup"><span data-stu-id="6238e-108">The certificate chain.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationCertificateChain">
      <MemberSignature Language="C#" Value="public override System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Security.Cryptography.X509Certificates.X509Certificate2Collection GetAuthenticationCertificateChain() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderX509Certificate.GetAuthenticationCertificateChain" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetAuthenticationCertificateChain () As X509Certificate2Collection" />
      <MemberSignature Language="F#" Value="override this.GetAuthenticationCertificateChain : unit -&gt; System.Security.Cryptography.X509Certificates.X509Certificate2Collection" Usage="securityProviderX509Certificate.GetAuthenticationCertificateChain " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2Collection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6238e-109">TLS デバイス認証を使用する証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="6238e-109">Gets the certificate used for TLS device authentication.</span></span>
            </summary>
        <returns><span data-ttu-id="6238e-110">TLS の通信中に使用されるクライアント証明書。</span><span class="sxs-lookup"><span data-stu-id="6238e-110">The client certificate used during TLS communications.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>