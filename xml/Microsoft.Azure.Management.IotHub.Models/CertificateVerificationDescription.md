<Type Name="CertificateVerificationDescription" FullName="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription">
  <TypeSignature Language="C#" Value="public class CertificateVerificationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateVerificationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateVerificationDescription" />
  <TypeSignature Language="F#" Value="type CertificateVerificationDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92873-101">リーフの JSON でシリアル化された証明書</span><span class="sxs-lookup"><span data-stu-id="92873-101">The JSON-serialized leaf certificate</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateVerificationDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92873-102">CertificateVerificationDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92873-102">Initializes a new instance of the CertificateVerificationDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateVerificationDescription (string certificate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificate As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription : string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" Usage="new Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificate" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificate"><span data-ttu-id="92873-103">X509 の base 64 形式の .cer ファイルまたは単なる .pem ファイル コンテンツ証明書します。</span><span class="sxs-lookup"><span data-stu-id="92873-103">base-64 representation of X509 certificate .cer file or just .pem file content.</span></span></param>
        <summary>
            <span data-ttu-id="92873-104">CertificateVerificationDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92873-104">Initializes a new instance of the CertificateVerificationDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public string Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As String" />
      <MemberSignature Language="F#" Value="member this.Certificate : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92873-105">取得または設定の base 64 形式の X509 証明書の .cer ファイルまたはコンテンツ .pem ファイルだけです。</span><span class="sxs-lookup"><span data-stu-id="92873-105">Gets or sets base-64 representation of X509 certificate .cer file or just .pem file content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>