<Type Name="OSProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile">
  <TypeSignature Language="C#" Value="public class OSProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class OSProfile" />
  <TypeSignature Language="F#" Value="type OSProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="59892-101">OS プロファイルをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="59892-101">Describes an OS profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="59892-102">OSProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="59892-102">Initializes a new instance of the OSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSProfile (string computerName = null, string adminUsername = null, string adminPassword = null, string customData = null, Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration windowsConfiguration = null, Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration linuxConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; secrets = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computerName, string adminUsername, string adminPassword, string customData, class Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration windowsConfiguration, class Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration linuxConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; secrets) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration,Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile : string * string * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration * Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile (computerName, adminUsername, adminPassword, customData, windowsConfiguration, linuxConfiguration, secrets)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computerName" Type="System.String" />
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="adminPassword" Type="System.String" />
        <Parameter Name="customData" Type="System.String" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration" />
        <Parameter Name="linuxConfiguration" Type="Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="computerName"><span data-ttu-id="59892-103">仮想マシンのホスト OS を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-103">Specifies the host OS name of the virtual machine.</span></span></param>
        <param name="adminUsername"><span data-ttu-id="59892-104">管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-104">Specifies the name of the administrator account.</span></span></param>
        <param name="adminPassword"><span data-ttu-id="59892-105">管理者アカウントのパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-105">Specifies the password of the administrator account.</span></span></param>
        <param name="customData"><span data-ttu-id="59892-106">カスタム データの base 64 でエンコードされた文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-106">Specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="59892-107">Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。</span><span class="sxs-lookup"><span data-stu-id="59892-107">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="59892-108">バイナリ配列の最大長は 65535 バイトです。</span><span class="sxs-lookup"><span data-stu-id="59892-108">The maximum length of the binary array is 65535 bytes</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="59892-109">OS プロファイルの Windows の構成。</span><span class="sxs-lookup"><span data-stu-id="59892-109">The Windows configuration of the OS profile.</span></span></param>
        <param name="linuxConfiguration"><span data-ttu-id="59892-110">OS プロファイルの Linux 構成します。</span><span class="sxs-lookup"><span data-stu-id="59892-110">The Linux configuration of the OS profile.</span></span></param>
        <param name="secrets"><span data-ttu-id="59892-111">VM への追加の証明書の一覧です。</span><span class="sxs-lookup"><span data-stu-id="59892-111">The list of certificates for addition to the VM.</span></span></param>
        <summary>
            <span data-ttu-id="59892-112">OSProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="59892-112">Initializes a new instance of the OSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminPassword">
      <MemberSignature Language="C#" Value="public string AdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.AdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminPassword : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.AdminPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-113">取得または設定は、管理者アカウントのパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-113">Gets or sets specifies the password of the administrator account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.AdminUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-114">取得または設定は、管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-114">Gets or sets specifies the name of the administrator account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-115">取得または設定、ホスト OS、仮想マシンの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-115">Gets or sets specifies the host OS name of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomData">
      <MemberSignature Language="C#" Value="public string CustomData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.CustomData" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomData As String" />
      <MemberSignature Language="F#" Value="member this.CustomData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.CustomData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-116">取得または設定は、カスタム データの base 64 でエンコードされた文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="59892-116">Gets or sets specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="59892-117">Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。</span><span class="sxs-lookup"><span data-stu-id="59892-117">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="59892-118">バイナリ配列の最大長は 65535 バイトです。</span><span class="sxs-lookup"><span data-stu-id="59892-118">The maximum length of the binary array is 65535 bytes</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration LinuxConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration LinuxConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.LinuxConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxConfiguration As LinuxConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxConfiguration : Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.LinuxConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.LinuxConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-119">取得または OS プロファイルの Linux の構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="59892-119">Gets or sets the Linux configuration of the OS profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of VaultSecretGroup)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.Secrets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secrets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-120">取得または VM に追加するための証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="59892-120">Gets or sets the list of certificates for addition to the VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59892-121">取得または OS プロファイルの Windows の構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="59892-121">Gets or sets the Windows configuration of the OS profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>