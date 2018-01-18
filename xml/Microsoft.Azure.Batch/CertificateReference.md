<Type Name="CertificateReference" FullName="Microsoft.Azure.Batch.CertificateReference">
  <TypeSignature Language="C#" Value="public class CertificateReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CertificateReference" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateReference" />
  <TypeSignature Language="F#" Value="type CertificateReference = class&#xA;    interface ITransportObjectProvider&lt;CertificateReference&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="854d8-101">Azure Batch サービスの証明書オブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="854d8-101">Represents a certificate object of the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="854d8-102"><see cref="T:Microsoft.Azure.Batch.CertificateReference" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="854d8-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.CertificateReference" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference (Microsoft.Azure.Batch.Certificate baseCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Certificate baseCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateReference.#ctor(Microsoft.Azure.Batch.Certificate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseCertificate As Certificate)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.CertificateReference : Microsoft.Azure.Batch.Certificate -&gt; Microsoft.Azure.Batch.CertificateReference" Usage="new Microsoft.Azure.Batch.CertificateReference baseCertificate" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseCertificate" Type="Microsoft.Azure.Batch.Certificate" />
      </Parameters>
      <Docs>
        <param name="baseCertificate"><span data-ttu-id="854d8-103">サムプリントと ThumbprintAlgorithm CertificateReference プロパティの初期値を提供します。</span><span class="sxs-lookup"><span data-stu-id="854d8-103">Provides initial values for the CertificateReference properties Thumbprint and ThumbprintAlgorithm.</span></span></param>
        <summary>
            <span data-ttu-id="854d8-104">既定のプロパティ値を持つ CertificateReference のインスタンスをインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="854d8-104">Instantiates an instance of CertificateReference with default property values.</span></span>  
            <span data-ttu-id="854d8-105">サムプリントと ThumbprintAlgorithm プロパティの値は、指定された基本証明書から取得されます。</span><span class="sxs-lookup"><span data-stu-id="854d8-105">Values for the Thumbprint and ThumbprintAlgorithm properties are taken from the provided base certificate.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertStoreLocation&gt; StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertStoreLocation&gt; StoreLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateReference.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As Nullable(Of CertStoreLocation)" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : Nullable&lt;Microsoft.Azure.Batch.Common.CertStoreLocation&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateReference.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertStoreLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="854d8-106">取得または設定、<see cref="T:Microsoft.Azure.Batch.Common.CertStoreLocation" />証明書のです。</span><span class="sxs-lookup"><span data-stu-id="854d8-106">Gets or sets the <see cref="T:Microsoft.Azure.Batch.Common.CertStoreLocation" /> for the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateReference.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="Microsoft.Azure.Batch.CertificateReference.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="854d8-107">取得またはの証明書ストアの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="854d8-107">Gets or sets the name of the name of the certificate store.</span></span> <span data-ttu-id="854d8-108">それに<see cref="T:System.Security.Cryptography.X509Certificates.StoreName" />値は、カスタム ストア名を持つことができます。</span><span class="sxs-lookup"><span data-stu-id="854d8-108">Besides <see cref="T:System.Security.Cryptography.X509Certificates.StoreName" /> the value can have a custom store name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateReference.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.CertificateReference.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="854d8-109">取得または証明書の証明書の拇印プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="854d8-109">Gets or sets the certificate thumbprint property of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateReference.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.CertificateReference.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="854d8-110">取得または証明書のサムプリント アルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="854d8-110">Gets or sets the certificate thumbprint algorithm.</span></span> <span data-ttu-id="854d8-111">現在 sha1 は、唯一サポートされているアルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="854d8-111">Currently sha1 is the only supported algorithm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visibility">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateVisibility&gt; Visibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateVisibility&gt; Visibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateReference.Visibility" />
      <MemberSignature Language="VB.NET" Value="Public Property Visibility As Nullable(Of CertificateVisibility)" />
      <MemberSignature Language="F#" Value="member this.Visibility : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateVisibility&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateReference.Visibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateVisibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="854d8-112">取得またはがインストールされている証明書のプライベート データにアクセスするユーザーのセットを設定します。</span><span class="sxs-lookup"><span data-stu-id="854d8-112">Gets or sets the set of users that can get to the private data of the installed certificate.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>