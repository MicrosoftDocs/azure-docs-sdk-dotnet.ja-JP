<Type Name="IssuerElement" FullName="Microsoft.ServiceBus.Configuration.IssuerElement">
  <TypeSignature Language="C#" Value="public class IssuerElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.IssuerElement" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type IssuerElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="bd51a-101">Azure Service Bus のトークンの発行者を説明する構成要素。</span><span class="sxs-lookup"><span data-stu-id="bd51a-101">A configuration element that describes an issuer of a token for the Azure Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.IssuerElement.Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string with get, set" Usage="Microsoft.ServiceBus.Configuration.IssuerElement.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerAddress", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=2048, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd51a-102">取得またはトークンの発行者の URI アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="bd51a-102">Gets or sets the URI address of the token issuer.</span></span></summary>
        <value><span data-ttu-id="bd51a-103">トークン発行者の URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="bd51a-103">The URI address of the token issuer.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (System.Configuration.ConfigurationElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class System.Configuration.ConfigurationElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.IssuerElement.CopyFrom(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (from As ConfigurationElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : System.Configuration.ConfigurationElement -&gt; unit" Usage="issuerElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Configuration.ConfigurationElement" />
      </Parameters>
      <Docs>
        <param name="from"> <span data-ttu-id="bd51a-104">コンテンツをコピーする構成要素。</span><span class="sxs-lookup"><span data-stu-id="bd51a-104">The configuration element to copy the contents from.</span></span></param>
        <summary><span data-ttu-id="bd51a-105">この構成要素に指定された構成要素の内容をコピーします。</span><span class="sxs-lookup"><span data-stu-id="bd51a-105">Copies the contents of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.IssuerElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.IssuerElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd51a-106">この構成要素に含まれるプロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="bd51a-106">Gets the collection of properties contained in this configuration element.</span></span></summary>
        <value><span data-ttu-id="bd51a-107">この構成要素に含まれるプロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="bd51a-107">The collection of properties contained in this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>