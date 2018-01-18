<Type Name="IssuerParameters" FullName="Microsoft.Azure.KeyVault.Models.IssuerParameters">
  <TypeSignature Language="C#" Value="public class IssuerParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerParameters" />
  <TypeSignature Language="F#" Value="type IssuerParameters = class" />
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
            <span data-ttu-id="17053-101">パラメーターが X509 の発行者の証明書のコンポーネントです。</span><span class="sxs-lookup"><span data-stu-id="17053-101">Parameters for the issuer of the X509 component of a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17053-102">IssuerParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17053-102">Initializes a new instance of the IssuerParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerParameters (string name = null, string certificateType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string certificateType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional certificateType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerParameters : string * string -&gt; Microsoft.Azure.KeyVault.Models.IssuerParameters" Usage="new Microsoft.Azure.KeyVault.Models.IssuerParameters (name, certificateType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="17053-103">参照されている発行者オブジェクトまたは予約済みの名前の名前'たとえば、Self' または 'Unknown' です。</span><span class="sxs-lookup"><span data-stu-id="17053-103">Name of the referenced issuer object or reserved names; for example, 'Self' or 'Unknown'.</span></span></param>
        <param name="certificateType"><span data-ttu-id="17053-104">発行者プロバイダーから要求する証明書の種類。</span><span class="sxs-lookup"><span data-stu-id="17053-104">Type of certificate to be requested from the issuer provider.</span></span></param>
        <summary>
            <span data-ttu-id="17053-105">IssuerParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17053-105">Initializes a new instance of the IssuerParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateType">
      <MemberSignature Language="C#" Value="public string CertificateType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerParameters.CertificateType" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateType As String" />
      <MemberSignature Language="F#" Value="member this.CertificateType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerParameters.CertificateType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cty")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17053-106">取得または発行者プロバイダーから要求される証明書の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="17053-106">Gets or sets type of certificate to be requested from the issuer provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17053-107">参照されている発行者オブジェクトの名前または予約済みの名前です。 取得または設定'たとえば、Self' または 'Unknown' です。</span><span class="sxs-lookup"><span data-stu-id="17053-107">Gets or sets name of the referenced issuer object or reserved names; for example, 'Self' or 'Unknown'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>