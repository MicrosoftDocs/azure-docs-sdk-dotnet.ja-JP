<Type Name="OSProfile" FullName="Microsoft.Azure.Management.Compute.Models.OSProfile">
  <TypeSignature Language="C#" Value="public class OSProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.OSProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class OSProfile" />
  <TypeSignature Language="F#" Value="type OSProfile = class" />
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
            バーチャル マシンのオペレーティング システムの設定を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSProfile.#ctor" />
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
            OSProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSProfile (string computerName = null, string adminUsername = null, string adminPassword = null, string customData = null, Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration = null, Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computerName, string adminUsername, string adminPassword, string customData, class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration windowsConfiguration, class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration linuxConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; secrets) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSProfile.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.WindowsConfiguration,Microsoft.Azure.Management.Compute.Models.LinuxConfiguration,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VaultSecretGroup})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.OSProfile : string * string * string * string * Microsoft.Azure.Management.Compute.Models.WindowsConfiguration * Microsoft.Azure.Management.Compute.Models.LinuxConfiguration * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; -&gt; Microsoft.Azure.Management.Compute.Models.OSProfile" Usage="new Microsoft.Azure.Management.Compute.Models.OSProfile (computerName, adminUsername, adminPassword, customData, windowsConfiguration, linuxConfiguration, secrets)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computerName" Type="System.String" />
        <Parameter Name="adminUsername" Type="System.String" />
        <Parameter Name="adminPassword" Type="System.String" />
        <Parameter Name="customData" Type="System.String" />
        <Parameter Name="windowsConfiguration" Type="Microsoft.Azure.Management.Compute.Models.WindowsConfiguration" />
        <Parameter Name="linuxConfiguration" Type="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration" />
        <Parameter Name="secrets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="computerName">仮想マシンのホスト OS を指定します。 &lt;ブラジル&gt;&lt;br&gt; **(Windows) の最大長:** 15 文字&lt;br&gt;&lt;br&gt; **(Linux) の最大長:**64 文字です。 &lt;ブラジル&gt;&lt;br&gt;の名前付け規則および制限を参照してください[Azure インフラストラクチャ サービスの実装のガイドライン](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-infrastructure-subscription-accounts-guidelines?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#1-naming-conventions)です。</param>
        <param name="adminUsername">管理者アカウントの名前を指定します。 &lt;ブラジル&gt;&lt;br&gt; **Windows 限定の制限:**で終わることはできません"です"。&lt;br&gt;&lt;br&gt; **値を許可されていません:** "administrator"、"admin"、"user"、"user1"、"test"、"user2"、"test1"、"user3"、"admin1"、「1」、「123」、"a"、"actuser"、"adm"、"admin2"、"aspnet"、"backup"、「コンソール」、"david"、"guest"、"john"、「所有者」、"root"、"server"、"sql"、「サポート」、"support_388945a0"、"sys"、「test2.」、"test3"、"user4"、"user5"です。 &lt;ブラジル&gt;&lt;br&gt; **(Linux) の長さ:** 1 文字&lt;br&gt;&lt;br&gt; **(Linux) の最大長:**64 文字&lt;br&gt;&lt;br&gt; **(Windows) の最大長:** 20 文字&lt;br&gt;&lt;br&gt;&lt;li&gt; Linux VM にルート アクセスを参照してください[なルート特権を使用して、Azure での Linux 仮想マシンで](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&lt;br&gt;&lt;li&gt;用、。一覧のこのフィールドには使用できません Linux 上の組み込みのシステム ユーザーを参照してください[Azure 上の Linux のユーザー名を選択する。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</param>
        <param name="adminPassword">管理者アカウントのパスワードを指定します。 &lt;ブラジル&gt;&lt;br&gt; **(Windows) の長さ:** 8 文字&lt;br&gt;&lt;br&gt; **(Linux) の長さ。** 6 文字&lt;br&gt;&lt;br&gt; **(Windows) の最大長:** 123 文字&lt;br&gt;&lt;ブラジル&gt; **(Linux) の最大長:** 72 文字&lt;br&gt;&lt;br&gt; **複雑さの要件:** 4 台のうち 3次に示す条件が満たされる必要があります&lt;br&gt;低い文字が含まれて&lt;br&gt;上限文字が含まれて&lt;br&gt;数字がある&lt;br&gt;が、(正規表現の一致 [\W_]) の特殊文字&lt;br&gt;&lt;br&gt; **値を許可されていません:** "abc@123"、"P@$$w0rd"、"P@ssw0rd「,」P@ssword123"、"Pa$ $word"、"pass@word1"、"Password!"、"Password1"、"Password22"、"iloveyou!"
            &lt;ブラジル&gt;&lt;br&gt;のパスワードをリセットするには、次を参照してください[、リモート デスクトップ サービス、または Windows 仮想マシンでは、そのログイン パスワードをリセットする方法](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;ブラジル。&gt;ルート パスワードをリセットするため、次を参照してください[ユーザーの管理、SSH、およびチェックや VMAccess 拡張機能を使用して Azure Linux Vm 上のディスクの修復。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)</param>
        <param name="customData">カスタム データの base 64 でエンコードされた文字列を指定します。 Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。 バイナリ配列の最大長は、サイズが 65535 バイトです。 &lt;ブラジル&gt;&lt;br&gt; VM のクラウド init を使用して、参照してください[クラウド init を使用して Linux VM を作成中にカスタマイズするには](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)</param>
        <param name="windowsConfiguration">仮想マシン上の Windows オペレーティング システムの設定を指定します。</param>
        <param name="linuxConfiguration">バーチャル マシンに Linux オペレーティング システムの設定を指定します。 &lt;ブラジル&gt;&lt;br&gt;サポートされている Linux ディストリビューションの一覧は、次を参照してください[Azure-Endorsed ディストリビューションで Linux](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; 。承認されている非配布を実行するため、次を参照してください。 [Non-Endorsed 分布について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。</param>
        <param name="secrets">バーチャル マシンにインストールする必要がある証明書を指定します。</param>
        <summary>
            OSProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminPassword">
      <MemberSignature Language="C#" Value="public string AdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.AdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminPassword : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.AdminPassword" />
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
            取得または設定は、管理者アカウントのパスワードを指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の長さ:** 8 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の長さ:** 6 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の最大長:** 123 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の最大長:** 72 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**複雑さの要件:**以下の 4 台のうち 3 の条件が満たされる必要があります&amp;lt; br&amp;gt;下の文字が含まれて&amp;lt; br&amp;gt;上の文字が含まれて&amp;lt; br&amp;gt;数字がある&amp;lt; br&amp;gt;特殊文字 (正規表現の一致 [\W_]) を含む&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**値を許可されていません:** "abc@123"、"P@$$w0rd"、"P@ssw0rd「,」P@ssword123"、"Pa$ $word"、"pass@word1"、"Password!"、"Password1"、"Password22"、"iloveyou!"
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;パスワードをリセットするを参照してください[、リモート デスクトップ サービス、または Windows 仮想マシンでは、そのログイン パスワードをリセットする方法](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-reset-rdp?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;ルート パスワードをリセットするため、次を参照してください[ユーザーの管理、SSH、およびチェックや VMAccess 拡張機能を使用して Azure Linux Vm 上のディスクの修復。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-vmaccess-extension?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#reset-root-password)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUsername">
      <MemberSignature Language="C#" Value="public string AdminUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.AdminUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUsername As String" />
      <MemberSignature Language="F#" Value="member this.AdminUsername : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.AdminUsername" />
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
            取得または設定は、管理者アカウントの名前を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows 限定の制限:**で終わることはできません"です"。&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**値を許可されていません:** "administrator"、"admin"、"user"、"user1"、"test"、"user2"、"test1"、"user3"、"admin1"、「1」、「123」、"a"、"actuser"、"adm"、"admin2"、"aspnet"、"backup"、"console"、"david"、"guest"、"john"、"所有者"、"root"、"server"、"sql"、「サポート」、"support_388945a0"、"sys"、「test2.」、"test3"、"user4"、"user5"です。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の長さ:** 1 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の最大長:** 64 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の最大長:** 20 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;&amp;lt; li&amp;gt;Linux VM にルート アクセスを参照してください[なルート特権を使用して、Azure での Linux 仮想マシンで](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-use-root-privileges?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)&amp;lt; br&amp;gt;&amp; 。lt; li&amp;gt;このフィールドには使用できません Linux 上の組み込みのシステム ユーザーの一覧は、次を参照してください[Azure 上の Linux のユーザー名を選択する。](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-usernames?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または設定、ホスト OS、仮想マシンの名前を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Windows) の最大長:** 15 文字&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**(Linux) の最大長:** 64 文字です。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;名前付け規則および制限を参照してください[Azure インフラストラクチャ サービスの実装のガイドライン](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-infrastructure-subscription-accounts-guidelines?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json#1-naming-conventions)です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomData">
      <MemberSignature Language="C#" Value="public string CustomData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.CustomData" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomData As String" />
      <MemberSignature Language="F#" Value="member this.CustomData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.CustomData" />
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
            取得または設定は、カスタム データの base 64 でエンコードされた文字列を指定します。 Base 64 でエンコードされた文字列は、仮想マシン上のファイルとして保存されるバイナリ配列にデコードされます。 バイナリ配列の最大長は、サイズが 65535 バイトです。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;VM のクラウド init を使用して、参照してください[クラウド init を使用して Linux VM を作成中にカスタマイズするには](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-using-cloud-init?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.LinuxConfiguration LinuxConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.LinuxConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxConfiguration As LinuxConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxConfiguration : Microsoft.Azure.Management.Compute.Models.LinuxConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.LinuxConfiguration" />
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
            取得または設定は、バーチャル マシンに Linux オペレーティング システムの設定を指定します。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;サポートされている Linux ディストリビューションの一覧は、次を参照してください[Azure-Endorsed ディストリビューションで Linux](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;承認されている非配布を実行するため、次を参照してください。 [Non-Endorsed 分布について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secrets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; Secrets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.Secrets" />
      <MemberSignature Language="VB.NET" Value="Public Property Secrets As IList(Of VaultSecretGroup)" />
      <MemberSignature Language="F#" Value="member this.Secrets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VaultSecretGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.Secrets" />
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
            取得または設定は、バーチャル マシンにインストールする必要がある証明書を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.WindowsConfiguration WindowsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSProfile.WindowsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsConfiguration As WindowsConfiguration" />
      <MemberSignature Language="F#" Value="member this.WindowsConfiguration : Microsoft.Azure.Management.Compute.Models.WindowsConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSProfile.WindowsConfiguration" />
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
            取得または設定は、仮想マシンで Windows オペレーティング システムの設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>