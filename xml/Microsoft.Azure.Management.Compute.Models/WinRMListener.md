<Type Name="WinRMListener" FullName="Microsoft.Azure.Management.Compute.Models.WinRMListener">
  <TypeSignature Language="C#" Value="public class WinRMListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WinRMListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.WinRMListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WinRMListener" />
  <TypeSignature Language="F#" Value="type WinRMListener = class" />
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
            <span data-ttu-id="e0a48-101">プロトコルと Windows リモート管理のリスナーの拇印について説明します</span><span class="sxs-lookup"><span data-stu-id="e0a48-101">Describes Protocol and thumbprint of Windows Remote Management listener</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor" />
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
            <span data-ttu-id="e0a48-102">WinRMListener クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e0a48-102">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener (Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol = null, string certificateUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol, string certificateUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.ProtocolTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As Nullable(Of ProtocolTypes) = null, Optional certificateUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.WinRMListener : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.WinRMListener" Usage="new Microsoft.Azure.Management.Compute.Models.WinRMListener (protocol, certificateUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;" />
        <Parameter Name="certificateUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="e0a48-103">リスナーのプロトコルを指定します。</span><span class="sxs-lookup"><span data-stu-id="e0a48-103">Specifies the protocol of listener.</span></span>
            <span data-ttu-id="e0a48-104">&lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;**http** &lt;br&gt;&lt;br&gt; **https**です。</span><span class="sxs-lookup"><span data-stu-id="e0a48-104">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;**http** &lt;br&gt;&lt;br&gt; **https**.</span></span> <span data-ttu-id="e0a48-105">使用可能な値が含まれます 'Http'、'Https'。</span><span class="sxs-lookup"><span data-stu-id="e0a48-105">Possible values include: 'Http', 'Https'</span></span></param>
        <param name="certificateUrl"><span data-ttu-id="e0a48-106">これは、シークレットとして Key Vault にアップロードされている証明書の URL です。</span><span class="sxs-lookup"><span data-stu-id="e0a48-106">This is the URL of a certificate that has been uploaded to Key Vault as a secret.</span></span> <span data-ttu-id="e0a48-107">参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。</span><span class="sxs-lookup"><span data-stu-id="e0a48-107">For adding a secret to the Key Vault, see [Add a key or secret to the key vault](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).</span></span>
            <span data-ttu-id="e0a48-108">証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64 でエンコードされた証明&gt;"、&lt;br&gt; "dataType":"pfx"&lt;br&gt; "password":"&lt;pfx ファイル パスワード&gt;"&lt;br&gt;}</span><span class="sxs-lookup"><span data-stu-id="e0a48-108">In this case, your certificate needs to be It is the Base64 encoding of the following JSON Object which is encoded in UTF-8: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64-encoded-certificate&gt;",&lt;br&gt; "dataType":"pfx",&lt;br&gt; "password":"&lt;pfx-file-password&gt;"&lt;br&gt;}</span></span></param>
        <summary>
            <span data-ttu-id="e0a48-109">WinRMListener クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e0a48-109">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
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
            <span data-ttu-id="e0a48-110">取得または設定は、シークレットとして Key Vault にアップロードされている証明書の URL になります。</span><span class="sxs-lookup"><span data-stu-id="e0a48-110">Gets or sets this is the URL of a certificate that has been uploaded to Key Vault as a secret.</span></span> <span data-ttu-id="e0a48-111">参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。</span><span class="sxs-lookup"><span data-stu-id="e0a48-111">For adding a secret to the Key Vault, see [Add a key or secret to the key vault](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).</span></span>
            <span data-ttu-id="e0a48-112">証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;{&amp;lt; br&amp;gt;"data":"&amp;lt;Base64 でエンコードされた証明&amp;gt;"、&amp;lt; br&amp;gt;"dataType":"pfx"&amp;lt; br&amp;gt;"password":"&amp;lt; pfx ファイル パスワード&amp;gt;"&amp;lt; br&amp;gt;}</span><span class="sxs-lookup"><span data-stu-id="e0a48-112">In this case, your certificate needs to be It is the Base64 encoding of the following JSON Object which is encoded in UTF-8: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; {&amp;lt;br&amp;gt; "data":"&amp;lt;Base64-encoded-certificate&amp;gt;",&amp;lt;br&amp;gt; "dataType":"pfx",&amp;lt;br&amp;gt; "password":"&amp;lt;pfx-file-password&amp;gt;"&amp;lt;br&amp;gt;}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As Nullable(Of ProtocolTypes)" />
      <MemberSignature Language="F#" Value="member this.Protocol : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0a48-113">取得または設定は、リスナーのプロトコルを指定します。</span><span class="sxs-lookup"><span data-stu-id="e0a48-113">Gets or sets specifies the protocol of listener.</span></span>
            <span data-ttu-id="e0a48-114">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;**http** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**https**です。</span><span class="sxs-lookup"><span data-stu-id="e0a48-114">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;**http** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **https**.</span></span> <span data-ttu-id="e0a48-115">使用可能な値が含まれます 'Http'、'Https'。</span><span class="sxs-lookup"><span data-stu-id="e0a48-115">Possible values include: 'Http', 'Https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>