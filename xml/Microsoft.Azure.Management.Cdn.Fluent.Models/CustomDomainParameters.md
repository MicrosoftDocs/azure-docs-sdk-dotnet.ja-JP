<Type Name="CustomDomainParameters" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters">
  <TypeSignature Language="C#" Value="public class CustomDomainParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDomainParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDomainParameters" />
  <TypeSignature Language="F#" Value="type CustomDomainParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ca8de-101">カスタム ドメインの作成または更新に必要な customDomain JSON オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ca8de-101">The customDomain JSON object required for custom domain creation or update.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca8de-102">CustomDomainParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca8de-102">Initializes a new instance of the CustomDomainParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDomainParameters (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters hostName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="ca8de-103">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="ca8de-103">The host name of the custom domain.</span></span> <span data-ttu-id="ca8de-104">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="ca8de-104">Must be a domain name.</span></span></param>
        <summary>
            <span data-ttu-id="ca8de-105">CustomDomainParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca8de-105">Initializes a new instance of the CustomDomainParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca8de-106">取得またはカスタムのドメインのホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca8de-106">Gets or sets the host name of the custom domain.</span></span> <span data-ttu-id="ca8de-107">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="ca8de-107">Must be a domain name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="customDomainParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca8de-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ca8de-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ca8de-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca8de-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>