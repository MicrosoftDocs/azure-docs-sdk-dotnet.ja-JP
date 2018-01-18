<Type Name="SharedSecretElement" FullName="Microsoft.ServiceBus.Configuration.SharedSecretElement">
  <TypeSignature Language="C#" Value="public class SharedSecretElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedSecretElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.SharedSecretElement" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedSecretElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SharedSecretElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6b8c5-101">使用するように構成するサービスまたはクライアント エンドポイントの資格情報を指定する構成要素、<see cref="T:Microsoft.ServiceBus.SharedSecretTokenProvider" />資格情報の種類。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-101">A configuration element that specifies the credentials for a service or client endpoint that is configured to use the <see cref="T:Microsoft.ServiceBus.SharedSecretTokenProvider" /> credential type.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.ServiceBus.Configuration.SharedSecretElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.ServiceBus.Configuration.SharedSecretElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.SharedSecretElement.CopyFrom(Microsoft.ServiceBus.Configuration.SharedSecretElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As SharedSecretElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.ServiceBus.Configuration.SharedSecretElement -&gt; unit" Usage="sharedSecretElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Configuration.SharedSecretElement" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="6b8c5-102">コピーされる共有シークレット構成要素。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-102">The shared secret configuration element to be copied.</span></span></param>
        <summary><span data-ttu-id="6b8c5-103">この構成要素に指定した共有シークレット構成要素の内容をコピーします。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-103">Copies the contents of the specified shared secret configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerName">
      <MemberSignature Language="C#" Value="public string IssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerName As String" />
      <MemberSignature Language="F#" Value="member this.IssuerName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerName", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6b8c5-104">取得または発行者名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-104">Gets or sets the issuer name.</span></span></summary>
        <value><span data-ttu-id="6b8c5-105">発行者の名前。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-105">The issuer name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerSecret">
      <MemberSignature Language="C#" Value="public string IssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.IssuerSecret : string with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerSecret", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6b8c5-106">取得または発行者のシークレット キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-106">Gets or sets the issuer secret key.</span></span></summary>
        <value><span data-ttu-id="6b8c5-107">発行者のシークレット キー。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-107">The issuer secret key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6b8c5-108">発行者名と発行者のシークレット キーが含まれているこの構成要素のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-108">Gets the properties of this configuration element that contain the issuer name and the issuer secret key.</span></span></summary>
        <value><span data-ttu-id="6b8c5-109">発行者名と発行者のシークレット キーを含む、この構成要素のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-109">The properties of this configuration element that contain the issuer name and the issuer secret key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenScope TokenScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.SharedSecretElement.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.ServiceBus.TokenScope with get, set" Usage="Microsoft.ServiceBus.Configuration.SharedSecretElement.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenScope", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6b8c5-110">取得またはトークンのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-110">Gets or sets the token scope.</span></span></summary>
        <value><span data-ttu-id="6b8c5-111">トークンのスコープです。</span><span class="sxs-lookup"><span data-stu-id="6b8c5-111">The token scope.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>