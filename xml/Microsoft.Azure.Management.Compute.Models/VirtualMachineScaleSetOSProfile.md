<Type Name="VirtualMachineScaleSetOSProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetOSProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetOSProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetOSProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14b13-101">仮想マシン スケール セットの OS プロファイルをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="14b13-101">Describes a virtual machine scale set OS profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14b13-102">VirtualMachineScaleSetOSProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="14b13-102">Initializes a new instance of the VirtualMachineScaleSetOSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSProfile (string computerNamePrefix = null, string adminUsername = null, string adminPassword = null, string customData = null, Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration = null, Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computerNamePrefix, string adminUsername, string adminPassword, string customData, class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration, class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.WindowsConfiguration,Microsoft.Azure.Management.Compute.Models.LinuxConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VaultSecretGroup})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile : string * string * string * string * Microsoft.Azure.Management.Compute.Models.WindowsConfiguration * Microsoft.Azure.Management.Compute.Models.LinuxConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile (computerNamePrefix, adminUsername, adminPassword, customData, windowsConfiguration, linuxConfiguration, secrets)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computerNamePrefix" Type="System.String" />
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="adminPassword" Type="System.String" />
        <Parameter Name="customData" Type="System.String" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration" />
        <Parameter Name="linuxConfiguration" Type="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="computerNamePrefix"><span data-ttu-id="14b13-103">スケール セット内のすべての仮想マシンのコンピューター名のプレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-103">Specifies the computer name prefix for all of the virtual machines in the scale set.</span></span> <span data-ttu-id="14b13-104">コンピューター名のプレフィックスは、1 ~ 15 文字にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="14b13-104">Computer name prefixes must be 1 to 15 characters long.</span></span></param>
        <param name="adminUsername"><span data-ttu-id="14b13-105">管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-105">Specifies the name of the administrator account.</span></span> <span data-ttu-id="14b13-106">&lt;ブラジル&gt;&lt;br&gt; **Windows 限定の制限:**で終わることはできません"です"。&lt;br&gt;&lt;br&gt; **値を許可されていません:** "administrator"、"admin"、"user"、"user1"、"test"、"user2"、"test1"、"user3"、"admin1"、「1」、「123」、"a"、"actuser"、"adm"、"admin2"、"aspnet"、"backup"、「コンソール」、"david"、"guest"、"john"、「所有者」、"root"、"server"、"sql"、「サポート」、"support_388945a0"、"sys"、「test2.」、"test3"、"user4"、"user5"です。</span><span class="sxs-lookup"><span data-stu-id="14b13-106">&lt;br&gt;&lt;br&gt; **Windows-only restriction:** Cannot end in "." &lt;br&gt;&lt;br&gt; **Disallowed values:** "administrator", "admin", "user", "user1", "test", "user2", "test1", "user3", "admin1", "1", "123", "a", "actuser", "adm", "admin2", "aspnet", "backup", "console", "david", "guest", "john", "owner", "root", "server", "sql", "support", "support_388945a0", "sys", "test2", "test3", "user4", "user5".</span></span> <span data-ttu-id="14b13-107">&lt;ブラジル&gt;&lt;br&gt; **(Linux) の長さ:** 1 文字&lt;br&gt;&lt;br&gt; **(Linux) の最大長:**64 文字&lt;br&gt;&lt;br&gt; **(Windows) の最大長:** 20 文字&lt;br&gt;&lt;br&gt;&lt;li&gt; Linux VM にルート アクセスを参照してください[なルート特権を使用して、Azure での Linux 仮想マシンで](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;br&gt;&lt;li&gt;用、。一覧のこのフィールドには使用できません Linux 上の組み込みのシステム ユーザーを参照してください[Azure 上の Linux のユーザー名を選択する。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="14b13-107">&lt;br&gt;&lt;br&gt; **Minimum-length (Linux):** 1  character &lt;br&gt;&lt;br&gt; **Max-length (Linux):** 64 characters &lt;br&gt;&lt;br&gt; **Max-length (Windows):** 20 characters &lt;br&gt;&lt;br&gt;&lt;li&gt; For root access to the Linux VM, see [Using root privileges on Linux virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;br&gt;&lt;li&gt; For a list of built-in system users on Linux that should not be used in this field, see [Selecting User Names for Linux on Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span></param>
        <param name="adminPassword"><span data-ttu-id="14b13-108">管理者アカウントのパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-108">Specifies the password of the administrator account.</span></span> <span data-ttu-id="14b13-109">&lt;ブラジル&gt;&lt;br&gt; **(Windows) の長さ:** 8 文字&lt;br&gt;&lt;br&gt; **(Linux) の長さ。** 6 文字&lt;br&gt;&lt;br&gt; **(Windows) の最大長:** 123 文字&lt;br&gt;&lt;ブラジル&gt; **(Linux) の最大長:** 72 文字&lt;br&gt;&lt;br&gt; **複雑さの要件:** 4 台のうち 3次に示す条件が満たされる必要があります&lt;br&gt;低い文字が含まれて&lt;br&gt;上限文字が含まれて&lt;br&gt;数字がある&lt;br&gt;が、(正規表現の一致 [\W_]) の特殊文字&lt;br&gt;&lt;br&gt; **値を許可されていません:** "abc@123"、"P@$$w0rd"、"P@ssw0rd「,」P@ssword123"、"Pa$ $word"、"pass@word1"、"Password!"、"Password1"、"Password22"、"iloveyou!"</span><span class="sxs-lookup"><span data-stu-id="14b13-109">&lt;br&gt;&lt;br&gt; **Minimum-length (Windows):** 8 characters &lt;br&gt;&lt;br&gt; **Minimum-length (Linux):** 6 characters &lt;br&gt;&lt;br&gt; **Max-length (Windows):** 123 characters &lt;br&gt;&lt;br&gt; **Max-length (Linux):** 72 characters &lt;br&gt;&lt;br&gt; **Complexity requirements:** 3 out of 4 conditions below need to be fulfilled &lt;br&gt; Has lower characters &lt;br&gt;Has upper characters &lt;br&gt; Has a digit &lt;br&gt; Has a special character (Regex match [\W_]) &lt;br&gt;&lt;br&gt; **Disallowed values:** "abc@123", "P@$$w0rd", "P@ssw0rd", "P@ssword123", "Pa$$word", "pass@word1", "Password!", "Password1", "Password22", "iloveyou!"</span></span>
            <span data-ttu-id="14b13-110">&lt;ブラジル&gt;&lt;br&gt;のパスワードをリセットするには、次を参照してください[、リモート デスクトップ サービス、または Windows 仮想マシンでは、そのログイン パスワードをリセットする方法](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;ブラジル。&gt;ルート パスワードをリセットするため、次を参照してください[ユーザーの管理、SSH、およびチェックや VMAccess 拡張機能を使用して Azure Linux Vm 上のディスクの修復。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span><span class="sxs-lookup"><span data-stu-id="14b13-110">&lt;br&gt;&lt;br&gt; For resetting the password, see [How to reset the Remote Desktop service or its login password in a Windows VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; For resetting root password, see [Manage users, SSH, and check or repair disks on Azure Linux VMs using the VMAccess Extension](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span></span></param>
        <param name="customData"><span data-ttu-id="14b13-111">カスタム データの base 64 でエンコードされた文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-111">Specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="14b13-112">Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。</span><span class="sxs-lookup"><span data-stu-id="14b13-112">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="14b13-113">バイナリ配列の最大長は、サイズが 65535 バイトです。</span><span class="sxs-lookup"><span data-stu-id="14b13-113">The maximum length of the binary array is 65535 bytes.</span></span> <span data-ttu-id="14b13-114">&lt;ブラジル&gt;&lt;br&gt; VM のクラウド init を使用して、参照してください[クラウド init を使用して Linux VM を作成中にカスタマイズするには](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="14b13-114">&lt;br&gt;&lt;br&gt; For using cloud-init for your VM, see [Using cloud-init to customize a Linux VM during creation](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span></param>
        <param name="windowsConfiguration"><span data-ttu-id="14b13-115">仮想マシン上の Windows オペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-115">Specifies Windows operating system settings on the virtual machine.</span></span></param>
        <param name="linuxConfiguration"><span data-ttu-id="14b13-116">バーチャル マシンに Linux オペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-116">Specifies the Linux operating system settings on the virtual machine.</span></span> <span data-ttu-id="14b13-117">&lt;ブラジル&gt;&lt;br&gt;サポートされている Linux ディストリビューションの一覧は、次を参照してください[Azure-Endorsed ディストリビューションで Linux](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; 。承認されている非配布を実行するため、次を参照してください。 [Non-Endorsed 分布について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="14b13-117">&lt;br&gt;&lt;br&gt;For a list of supported Linux distributions, see [Linux on Azure-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; For running non-endorsed distributions, see [Information for Non-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span></param>
        <param name="secrets"><span data-ttu-id="14b13-118">仮想マシン スケール セット内にインストールする必要がある証明書を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-118">Specifies set of certificates that should be installed onto the virtual machines in the scale set.</span></span></param>
        <summary>
            <span data-ttu-id="14b13-119">VirtualMachineScaleSetOSProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="14b13-119">Initializes a new instance of the VirtualMachineScaleSetOSProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminPassword">
      <MemberSignature Language="C#" Value="public string AdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminPassword : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="14b13-120">取得または設定は、管理者アカウントのパスワードを指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-120">Gets or sets specifies the password of the administrator account.</span></span>
            <span data-ttu-id="14b13-121">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の長さ:** 8 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の長さ:** 6 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の最大長:** 123 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の最大長:** 72 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**複雑さの要件:**以下の 4 台のうち 3 の条件が満たされる必要があります&amp;lt; br&amp;gt;下の文字が含まれて&amp;lt; br&amp;gt;上の文字が含まれて&amp;lt; br&amp;gt;数字がある&amp;lt; br&amp;gt;特殊文字 (正規表現の一致 [\W_]) を含む&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**値を許可されていません:** "abc@123"、"P@$$w0rd"、"P@ssw0rd「,」P@ssword123"、"Pa$ $word"、"pass@word1"、"Password!"、"Password1"、"Password22"、"iloveyou!"</span><span class="sxs-lookup"><span data-stu-id="14b13-121">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Windows):** 8 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Linux):** 6 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Windows):** 123 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Linux):** 72 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Complexity requirements:** 3 out of 4 conditions below need to be fulfilled &amp;lt;br&amp;gt; Has lower characters &amp;lt;br&amp;gt;Has upper characters &amp;lt;br&amp;gt; Has a digit &amp;lt;br&amp;gt; Has a special character (Regex match [\W_]) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Disallowed values:** "abc@123", "P@$$w0rd", "P@ssw0rd", "P@ssword123", "Pa$$word", "pass@word1", "Password!", "Password1", "Password22", "iloveyou!"</span></span>
            <span data-ttu-id="14b13-122">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;パスワードをリセットするを参照してください[、リモート デスクトップ サービス、または Windows 仮想マシンでは、そのログイン パスワードをリセットする方法](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;ルート パスワードをリセットするため、次を参照してください[ユーザーの管理、SSH、およびチェックや VMAccess 拡張機能を使用して Azure Linux Vm 上のディスクの修復。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span><span class="sxs-lookup"><span data-stu-id="14b13-122">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For resetting the password, see [How to reset the Remote Desktop service or its login password in a Windows VM](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For resetting root password, see [Manage users, SSH, and check or repair disks on Azure Linux VMs using the VMAccess Extension](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.AdminUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="14b13-123">取得または設定は、管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-123">Gets or sets specifies the name of the administrator account.</span></span>
            <span data-ttu-id="14b13-124">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows 限定の制限:**で終わることはできません"です"。&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**値を許可されていません:** "administrator"、"admin"、"user"、"user1"、"test"、"user2"、"test1"、"user3"、"admin1"、「1」、「123」、"a"、"actuser"、"adm"、"admin2"、"aspnet"、"backup"、"console"、"david"、"guest"、"john"、"所有者"、"root"、"server"、"sql"、「サポート」、"support_388945a0"、"sys"、「test2.」、"test3"、"user4"、"user5"です。</span><span class="sxs-lookup"><span data-stu-id="14b13-124">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Windows-only restriction:** Cannot end in "." &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Disallowed values:** "administrator", "admin", "user", "user1", "test", "user2", "test1", "user3", "admin1", "1", "123", "a", "actuser", "adm", "admin2", "aspnet", "backup", "console", "david", "guest", "john", "owner", "root", "server", "sql", "support", "support_388945a0", "sys", "test2", "test3", "user4", "user5".</span></span>
            <span data-ttu-id="14b13-125">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の長さ:** 1 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の最大長:** 64 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の最大長:** 20 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;&amp;lt; li&amp;gt;Linux VM にルート アクセスを参照してください[なルート特権を使用して、Azure での Linux 仮想マシンで](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;lt; br&amp;gt;&amp; 。lt; li&amp;gt;このフィールドには使用できません Linux 上の組み込みのシステム ユーザーの一覧は、次を参照してください[Azure 上の Linux のユーザー名を選択する。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="14b13-125">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Minimum-length (Linux):** 1 character &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Linux):** 64 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Max-length (Windows):** 20 characters &amp;lt;br&amp;gt;&amp;lt;br&amp;gt;&amp;lt;li&amp;gt; For root access to the Linux VM, see [Using root privileges on Linux virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;lt;br&amp;gt;&amp;lt;li&amp;gt; For a list of built-in system users on Linux that should not be used in this field, see [Selecting User Names for Linux on Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerNamePrefix">
      <MemberSignature Language="C#" Value="public string ComputerNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.ComputerNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerNamePrefix As String" />
      <MemberSignature Language="F#" Value="member this.ComputerNamePrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.ComputerNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computerNamePrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14b13-126">取得または設定は、スケール セット内のすべての仮想マシンのコンピューター名のプレフィックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-126">Gets or sets specifies the computer name prefix for all of the virtual machines in the scale set.</span></span> <span data-ttu-id="14b13-127">コンピューター名のプレフィックスは、1 ~ 15 文字にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="14b13-127">Computer name prefixes must be 1 to 15 characters long.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomData">
      <MemberSignature Language="C#" Value="public string CustomData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.CustomData" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomData As String" />
      <MemberSignature Language="F#" Value="member this.CustomData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.CustomData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="14b13-128">取得または設定は、カスタム データの base 64 でエンコードされた文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-128">Gets or sets specifies a base-64 encoded string of custom data.</span></span> <span data-ttu-id="14b13-129">Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。</span><span class="sxs-lookup"><span data-stu-id="14b13-129">The base-64 encoded string is decoded to a binary array that is saved as a file on the Virtual Machine.</span></span> <span data-ttu-id="14b13-130">バイナリ配列の最大長は、サイズが 65535 バイトです。</span><span class="sxs-lookup"><span data-stu-id="14b13-130">The maximum length of the binary array is 65535 bytes.</span></span> <span data-ttu-id="14b13-131">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;VM のクラウド init を使用して、参照してください[クラウド init を使用して Linux VM を作成中にカスタマイズするには](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span><span class="sxs-lookup"><span data-stu-id="14b13-131">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For using cloud-init for your VM, see [Using cloud-init to customize a Linux VM during creation](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.LinuxConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxConfiguration As LinuxConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxConfiguration : Microsoft.Azure.Management.Compute.Models.LinuxConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.LinuxConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.LinuxConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14b13-132">取得または設定は、バーチャル マシンに Linux オペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-132">Gets or sets specifies the Linux operating system settings on the virtual machine.</span></span> <span data-ttu-id="14b13-133">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;サポートされている Linux ディストリビューションの一覧は、次を参照してください[Azure-Endorsed ディストリビューションで Linux](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;承認されている非配布を実行するため、次を参照してください。 [Non-Endorsed 分布について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="14b13-133">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;For a list of supported Linux distributions, see [Linux on Azure-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For running non-endorsed distributions, see [Information for Non-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of VaultSecretGroup)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.Secrets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secrets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14b13-134">取得または設定は、仮想マシン スケール セット内にインストールする必要がある証明書を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-134">Gets or sets specifies set of certificates that should be installed onto the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Compute.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile.WindowsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.WindowsConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14b13-135">取得または設定は、仮想マシンで Windows オペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="14b13-135">Gets or sets specifies Windows operating system settings on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>