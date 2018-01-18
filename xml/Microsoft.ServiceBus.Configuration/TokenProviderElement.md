<Type Name="TokenProviderElement" FullName="Microsoft.ServiceBus.Configuration.TokenProviderElement">
  <TypeSignature Language="C#" Value="public class TokenProviderElement : System.ServiceModel.Configuration.ClientCredentialsElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenProviderElement extends System.ServiceModel.Configuration.ClientCredentialsElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TokenProviderElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenProviderElement&#xA;Inherits ClientCredentialsElement" />
  <TypeSignature Language="F#" Value="type TokenProviderElement = class&#xA;    inherit ClientCredentialsElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.ClientCredentialsElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="00662-101">Service Bus のトークン プロバイダーを指定する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="00662-101">Represents the configuration element that specifies the token provider for the Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TokenProviderElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="tokenProviderElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> <span data-ttu-id="00662-102">コンテンツをコピーする構成要素。</span><span class="sxs-lookup"><span data-stu-id="00662-102">The configuration element to copy the contents from.</span></span></param>
        <summary><span data-ttu-id="00662-103">この構成要素に指定された構成要素の内容をコピーします。</span><span class="sxs-lookup"><span data-stu-id="00662-103">Copies the contents of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElement.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElement.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("name", IsKey=true, IsRequired=false)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(InvalidCharacters=" ", MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00662-104">指定した名前を取得<see cref="T:Microsoft.ServiceBus.Configuration.TokenProviderElement" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00662-104">Gets the name of the specified <see cref="T:Microsoft.ServiceBus.Configuration.TokenProviderElement" /> object.</span></span></summary>
        <value><span data-ttu-id="00662-105">指定した<see cref="T:Microsoft.ServiceBus.Configuration.TokenProviderElement" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00662-105">The specified <see cref="T:Microsoft.ServiceBus.Configuration.TokenProviderElement" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00662-106">構成要素に含まれるプロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="00662-106">Gets the collection of properties contained in the configuration element.</span></span></summary>
        <value><span data-ttu-id="00662-107">構成要素に含まれるプロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="00662-107">The collection of properties contained in the configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement SharedAccessSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElement.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessSignature As SharedAccessSignatureElement" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElement.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sharedAccessSignature")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SharedAccessSignatureElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00662-108">共有アクセス署名の要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="00662-108">Gets the shared access signature element.</span></span></summary>
        <value><span data-ttu-id="00662-109">共有アクセス署名の要素。</span><span class="sxs-lookup"><span data-stu-id="00662-109">The shared access signature element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecret">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SharedSecretElement SharedSecret { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SharedSecretElement SharedSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElement.SharedSecret" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedSecret As SharedSecretElement" />
      <MemberSignature Language="F#" Value="member this.SharedSecret : Microsoft.ServiceBus.Configuration.SharedSecretElement" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElement.SharedSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sharedSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SharedSecretElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00662-110">トークン プロバイダー要素に含まれている共有シークレットの要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="00662-110">Gets the shared secret element contained in the token provider element.</span></span></summary>
        <value><span data-ttu-id="00662-111">トークン プロバイダー要素に含まれている共有シークレット要素。</span><span class="sxs-lookup"><span data-stu-id="00662-111">The shared secret element contained in the token provider element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsAuthentication">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WindowsElement WindowsAuthentication { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WindowsElement WindowsAuthentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElement.WindowsAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WindowsAuthentication As WindowsElement" />
      <MemberSignature Language="F#" Value="member this.WindowsAuthentication : Microsoft.ServiceBus.Configuration.WindowsElement" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElement.WindowsAuthentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("windowsAuthentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WindowsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="00662-112">この要素の Windows 認証の設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="00662-112">Gets the Windows authentication settings for this element.</span></span></summary>
        <value><span data-ttu-id="00662-113">この要素の Windows 認証の設定です。</span><span class="sxs-lookup"><span data-stu-id="00662-113">The Windows authentication settings for this element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>