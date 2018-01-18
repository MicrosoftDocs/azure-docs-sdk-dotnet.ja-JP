<Type Name="LinuxConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration">
  <TypeSignature Language="C#" Value="public class LinuxConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinuxConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.LinuxConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class LinuxConfiguration" />
  <TypeSignature Language="F#" Value="type LinuxConfiguration = class" />
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
            <span data-ttu-id="d0e40-101">バーチャル マシンに Linux オペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-101">Specifies the Linux operating system settings on the virtual machine.</span></span>
            <span data-ttu-id="d0e40-102">&lt;ブラジル&gt;&lt;br&gt;サポートされている Linux ディストリビューションの一覧は、次を参照してください[Azure-Endorsed ディストリビューションで Linux](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; 。承認されている非配布を実行するため、次を参照してください。 [Non-Endorsed 分布について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="d0e40-102">&lt;br&gt;&lt;br&gt;For a list of supported Linux distributions, see [Linux on Azure-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-endorsed-distros?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json) &lt;br&gt;&lt;br&gt; For running non-endorsed distributions, see [Information for Non-Endorsed Distributions](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-linux-create-upload-generic?toc=%2fazure%2fvirtual-machines%2flinux%2ftoc.json).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.#ctor" />
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
            <span data-ttu-id="d0e40-103">LinuxConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-103">Initializes a new instance of the LinuxConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxConfiguration (Nullable&lt;bool&gt; disablePasswordAuthentication = null, Microsoft.Azure.Management.Compute.Models.SshConfiguration ssh = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; disablePasswordAuthentication, class Microsoft.Azure.Management.Compute.Models.SshConfiguration ssh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.#ctor(System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.SshConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional disablePasswordAuthentication As Nullable(Of Boolean) = null, Optional ssh As SshConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.LinuxConfiguration : Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.SshConfiguration -&gt; Microsoft.Azure.Management.Compute.Models.LinuxConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.LinuxConfiguration (disablePasswordAuthentication, ssh)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disablePasswordAuthentication" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ssh" Type="Microsoft.Azure.Management.Compute.Models.SshConfiguration" />
      </Parameters>
      <Docs>
        <param name="disablePasswordAuthentication"><span data-ttu-id="d0e40-104">パスワード認証を無効にするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-104">Specifies whether password authentication should be disabled.</span></span></param>
        <param name="ssh"><span data-ttu-id="d0e40-105">Linux OS の SSH キーの構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-105">Specifies the ssh key configuration for a Linux OS.</span></span></param>
        <summary>
            <span data-ttu-id="d0e40-106">LinuxConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-106">Initializes a new instance of the LinuxConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePasswordAuthentication">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisablePasswordAuthentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisablePasswordAuthentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.DisablePasswordAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public Property DisablePasswordAuthentication As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisablePasswordAuthentication : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.DisablePasswordAuthentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disablePasswordAuthentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0e40-107">取得または設定は、パスワード認証を無効にするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="d0e40-107">Gets or sets specifies whether password authentication should be disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ssh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SshConfiguration Ssh { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SshConfiguration Ssh" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.Ssh" />
      <MemberSignature Language="VB.NET" Value="Public Property Ssh As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.Ssh : Microsoft.Azure.Management.Compute.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.Compute.Models.LinuxConfiguration.Ssh" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ssh")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0e40-108">取得または設定を指定します、ssh キーの Linux オペレーティング システムの構成。</span><span class="sxs-lookup"><span data-stu-id="d0e40-108">Gets or sets specifies the ssh key configuration for a Linux OS.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>