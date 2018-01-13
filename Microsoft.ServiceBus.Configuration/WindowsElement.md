<Type Name="WindowsElement" FullName="Microsoft.ServiceBus.Configuration.WindowsElement">
  <TypeSignature Language="C#" Value="public class WindowsElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WindowsElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WindowsElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d9263-101">Service bus の構成が windows 要素を表します。</span><span class="sxs-lookup"><span data-stu-id="d9263-101">Represents the windows element for the configuration of the service bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.ServiceBus.Configuration.WindowsElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.ServiceBus.Configuration.WindowsElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WindowsElement.CopyFrom(Microsoft.ServiceBus.Configuration.WindowsElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As WindowsElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.ServiceBus.Configuration.WindowsElement -&gt; unit" Usage="windowsElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Configuration.WindowsElement" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="d9263-102">Windows 要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="d9263-102">The windows element to copy.</span></span></param>
        <summary><span data-ttu-id="d9263-103">現在のインスタンスに指定されたウィンドウの要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="d9263-103">Copies the specified windows element into the current instance.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domain">
      <MemberSignature Language="C#" Value="public string Domain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Domain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.Domain" />
      <MemberSignature Language="VB.NET" Value="Public Property Domain As String" />
      <MemberSignature Language="F#" Value="member this.Domain : string with get, set" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.Domain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("domain", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-104">取得またはドメインを設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-104">Gets or sets the domain.</span></span></summary>
        <value><span data-ttu-id="d9263-105">ドメイン。</span><span class="sxs-lookup"><span data-stu-id="d9263-105">The domain.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("password", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-106">パスワードを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-106">Gets or sets the password.</span></span></summary>
        <value><span data-ttu-id="d9263-107">パスワード。</span><span class="sxs-lookup"><span data-stu-id="d9263-107">The password.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-108">取得または設定のプロパティのコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-108">Gets or sets the collection of configuration properties.</span></span></summary>
        <value><span data-ttu-id="d9263-109">構成プロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d9263-109">The collection of configuration properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsUris">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Configuration.StsUriElementCollection StsUris { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.StsUriElementCollection StsUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.StsUris" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property StsUris As StsUriElementCollection" />
      <MemberSignature Language="F#" Value="member this.StsUris : Microsoft.ServiceBus.Configuration.StsUriElementCollection" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.StsUris" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("stsUris", IsDefaultCollection=false, IsRequired=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.StsUriElementCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-110">取得またはセキュリティ トークン サービス (STS) URI のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-110">Gets or sets the collection of security token service (STS) URI.</span></span></summary>
        <value><span data-ttu-id="d9263-111">セキュリティ トークン サービス (STS) URI のコレクション。</span><span class="sxs-lookup"><span data-stu-id="d9263-111">The collection of security token service (STS) URI.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultCredentials">
      <MemberSignature Language="C#" Value="public bool UseDefaultCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultCredentials As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultCredentials : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.UseDefaultCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultCredentials", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-112">取得または既定の資格情報を使用するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-112">Gets or sets a value that indicates whether to use default credentials.</span></span></summary>
        <value><span data-ttu-id="d9263-113">既定の資格情報を使用する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="d9263-113">true if to use default credentials; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WindowsElement.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.WindowsElement.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("userName", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d9263-114">取得またはユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d9263-114">Gets or sets the username.</span></span></summary>
        <value><span data-ttu-id="d9263-115">ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="d9263-115">The username.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>