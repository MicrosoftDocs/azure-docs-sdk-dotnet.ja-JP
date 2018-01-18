<Type Name="CertificateCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type CertificateCreateOrUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="50f83-101">パラメーターは、作成または更新プログラムに渡されるか、証明書の操作を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="50f83-101">The parameters supplied to the create or update or replace certificate operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="50f83-102">CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="50f83-102">Initializes a new instance of the CertificateCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters (string name, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.#ctor(System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, properties As CertificateCreateOrUpdateProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters : string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties -&gt; Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters (name, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="50f83-103">必須の引数で CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="50f83-103">Initializes a new instance of the CertificateCreateOrUpdateParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f83-104">必須。</span><span class="sxs-lookup"><span data-stu-id="50f83-104">Required.</span></span> <span data-ttu-id="50f83-105">取得または証明書の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="50f83-105">Gets or sets the name of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As CertificateCreateOrUpdateProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties with get, set" Usage="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50f83-106">必須。</span><span class="sxs-lookup"><span data-stu-id="50f83-106">Required.</span></span> <span data-ttu-id="50f83-107">取得または証明書のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="50f83-107">Gets or sets the properties of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>