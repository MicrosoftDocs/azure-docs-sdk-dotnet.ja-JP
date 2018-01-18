<Type Name="VirtualMachineEncryptionConfiguration&lt;T&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class VirtualMachineEncryptionConfiguration&lt;T&gt; where T : VirtualMachineEncryptionConfiguration&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit VirtualMachineEncryptionConfiguration`1&lt;(class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1&lt;!T&gt;) T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class VirtualMachineEncryptionConfiguration(Of T)" />
  <TypeSignature Language="F#" Value="type VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;T&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
             <span data-ttu-id="eed7b-101">仮想マシンに適用されるを表すの暗号化構成を入力します。</span><span class="sxs-lookup"><span data-stu-id="eed7b-101">Type representing encryption configuration to be applied to a virtual machine.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected VirtualMachineEncryptionConfiguration (string keyVaultId, string aadClientId, string aadSecret);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string keyVaultId, string aadClientId, string aadSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (keyVaultId As String, aadClientId As String, aadSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt; : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt; (keyVaultId, aadClientId, aadSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="aadClientId" Type="System.String" />
        <Parameter Name="aadSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyVaultId"><span data-ttu-id="eed7b-102">ディスクの暗号化キーを格納する key vault のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-102">Resource id of the key vault to store the disk encryption key.</span></span></param>
        <param name="aadClientId"><span data-ttu-id="eed7b-103">Key vault にアクセスするには、アプリケーション クライアント id を AAD です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-103">AAD application client id to access the key vault.</span></span></param>
        <param name="aadSecret"><span data-ttu-id="eed7b-104">Key vault にアクセスする AAD アプリケーション クライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="eed7b-104">AAD application client secret to access the key vault.</span></span></param>
        <summary>
             <span data-ttu-id="eed7b-105">VirtualMachineEncryptionConfiguration を作成します。</span><span class="sxs-lookup"><span data-stu-id="eed7b-105">Creates VirtualMachineEncryptionConfiguration.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="aadClientId">
      <MemberSignature Language="C#" Value="protected string aadClientId;" />
      <MemberSignature Language="ILAsm" Value=".field family string aadClientId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.aadClientId" />
      <MemberSignature Language="VB.NET" Value="Protected aadClientId As String " />
      <MemberSignature Language="F#" Value="val mutable aadClientId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.aadClientId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadClientId">
      <MemberSignature Language="C#" Value="public string AadClientId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string AadClientId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.AadClientId" />
      <MemberSignature Language="VB.NET" Value="Public Function AadClientId () As String" />
      <MemberSignature Language="F#" Value="member this.AadClientId : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.AadClientId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-106">Key vault にアクセスする AAD アプリケーション クライアント id。</span><span class="sxs-lookup"><span data-stu-id="eed7b-106">The AAD application client id to access the key vault.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="aadSecret">
      <MemberSignature Language="C#" Value="protected string aadSecret;" />
      <MemberSignature Language="ILAsm" Value=".field family string aadSecret" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.aadSecret" />
      <MemberSignature Language="VB.NET" Value="Protected aadSecret As String " />
      <MemberSignature Language="F#" Value="val mutable aadSecret : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.aadSecret" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AadSecret">
      <MemberSignature Language="C#" Value="public string AadSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string AadSecret() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.AadSecret" />
      <MemberSignature Language="VB.NET" Value="Public Function AadSecret () As String" />
      <MemberSignature Language="F#" Value="member this.AadSecret : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.AadSecret " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-107">Key vault にアクセスする AAD アプリケーション クライアント シークレット。</span><span class="sxs-lookup"><span data-stu-id="eed7b-107">The AAD application client secret to access the key vault.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="encryptionAlgorithm">
      <MemberSignature Language="C#" Value="protected string encryptionAlgorithm;" />
      <MemberSignature Language="ILAsm" Value=".field family string encryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.encryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Protected encryptionAlgorithm As String " />
      <MemberSignature Language="F#" Value="val mutable encryptionAlgorithm : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.encryptionAlgorithm" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="keyEncryptionKeyURL">
      <MemberSignature Language="C#" Value="protected string keyEncryptionKeyURL;" />
      <MemberSignature Language="ILAsm" Value=".field family string keyEncryptionKeyURL" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.keyEncryptionKeyURL" />
      <MemberSignature Language="VB.NET" Value="Protected keyEncryptionKeyURL As String " />
      <MemberSignature Language="F#" Value="val mutable keyEncryptionKeyURL : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.keyEncryptionKeyURL" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKeyURL">
      <MemberSignature Language="C#" Value="public string KeyEncryptionKeyURL ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string KeyEncryptionKeyURL() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.KeyEncryptionKeyURL" />
      <MemberSignature Language="VB.NET" Value="Public Function KeyEncryptionKeyURL () As String" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKeyURL : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.KeyEncryptionKeyURL " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-108">キー (KEK) を保護するキーの資格情報コンテナーの url (暗号化)、ディスクの暗号化キー。</span><span class="sxs-lookup"><span data-stu-id="eed7b-108">Key vault url to the key (KEK) to protect (encrypt) the disk-encryption key.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="keyEncryptionKeyVaultId">
      <MemberSignature Language="C#" Value="protected string keyEncryptionKeyVaultId;" />
      <MemberSignature Language="ILAsm" Value=".field family string keyEncryptionKeyVaultId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.keyEncryptionKeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Protected keyEncryptionKeyVaultId As String " />
      <MemberSignature Language="F#" Value="val mutable keyEncryptionKeyVaultId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.keyEncryptionKeyVaultId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyEncryptionKeyVaultId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string KeyEncryptionKeyVaultId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.KeyEncryptionKeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Function KeyEncryptionKeyVaultId () As String" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKeyVaultId : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.KeyEncryptionKeyVaultId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-109">キーの暗号化キー (KEK) を保持する key vault のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-109">Resource id of the key vault holding key encryption key (KEK).</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="keyVaultId">
      <MemberSignature Language="C#" Value="protected string keyVaultId;" />
      <MemberSignature Language="ILAsm" Value=".field family string keyVaultId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.keyVaultId" />
      <MemberSignature Language="VB.NET" Value="Protected keyVaultId As String " />
      <MemberSignature Language="F#" Value="val mutable keyVaultId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.keyVaultId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string KeyVaultId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Function KeyVaultId () As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.KeyVaultId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-110">ディスクの暗号化キーを格納する key vault のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-110">Resource id of the key vault to store the disk encryption key.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultUrl">
      <MemberSignature Language="C#" Value="public string KeyVaultUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string KeyVaultUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.KeyVaultUrl" />
      <MemberSignature Language="VB.NET" Value="Public Function KeyVaultUrl () As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultUrl : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.KeyVaultUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-111">ディスクの暗号化キーを格納する、key vault の Url。</span><span class="sxs-lookup"><span data-stu-id="eed7b-111">Url to the key vault to store the disk encryption key.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="LinuxPassPhrase">
      <MemberSignature Language="C#" Value="public string LinuxPassPhrase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string LinuxPassPhrase() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.LinuxPassPhrase" />
      <MemberSignature Language="VB.NET" Value="Public Function LinuxPassPhrase () As String" />
      <MemberSignature Language="F#" Value="member this.LinuxPassPhrase : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.LinuxPassPhrase " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-112">Linux OS とデータ ディスクを暗号化するパスフレーズです。</span><span class="sxs-lookup"><span data-stu-id="eed7b-112">The pass phrase to encrypt Linux OS and data disks.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.OsType" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OsType () As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="abstract member OsType : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="virtualMachineEncryptionConfiguration.OsType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-113">オペレーティング システムの種類。</span><span class="sxs-lookup"><span data-stu-id="eed7b-113">The operating system type.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="passPhrase">
      <MemberSignature Language="C#" Value="protected string passPhrase;" />
      <MemberSignature Language="ILAsm" Value=".field family string passPhrase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.passPhrase" />
      <MemberSignature Language="VB.NET" Value="Protected passPhrase As String " />
      <MemberSignature Language="F#" Value="val mutable passPhrase : string" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.passPhrase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeEncryptionKeyEncryptAlgorithm">
      <MemberSignature Language="C#" Value="public string VolumeEncryptionKeyEncryptAlgorithm ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string VolumeEncryptionKeyEncryptAlgorithm() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.VolumeEncryptionKeyEncryptAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Function VolumeEncryptionKeyEncryptAlgorithm () As String" />
      <MemberSignature Language="F#" Value="member this.VolumeEncryptionKeyEncryptAlgorithm : unit -&gt; string" Usage="virtualMachineEncryptionConfiguration.VolumeEncryptionKeyEncryptAlgorithm " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-114">ディスク暗号化キーの暗号化に使用されるアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="eed7b-114">The algorithm used to encrypt the disk-encryption key.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="volumeType">
      <MemberSignature Language="C#" Value="protected Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType;" />
      <MemberSignature Language="ILAsm" Value=".field family valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.volumeType" />
      <MemberSignature Language="VB.NET" Value="Protected volumeType As DiskVolumeType " />
      <MemberSignature Language="F#" Value="val mutable volumeType : Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T (requires 'T :&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;'T&gt;)&gt;.volumeType" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType VolumeType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType VolumeType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.VolumeType" />
      <MemberSignature Language="VB.NET" Value="Public Function VolumeType () As DiskVolumeType" />
      <MemberSignature Language="F#" Value="member this.VolumeType : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType" Usage="virtualMachineEncryptionConfiguration.VolumeType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-115">暗号化操作を実行するボリュームの種類です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-115">Type of the volume to perform encryption operation.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithVolumeEncryptionKeyEncryptAlgorithm">
      <MemberSignature Language="C#" Value="public T WithVolumeEncryptionKeyEncryptAlgorithm (string encryptionAlgorithm);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !T WithVolumeEncryptionKeyEncryptAlgorithm(string encryptionAlgorithm) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.WithVolumeEncryptionKeyEncryptAlgorithm(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVolumeEncryptionKeyEncryptAlgorithm (encryptionAlgorithm As String) As T" />
      <MemberSignature Language="F#" Value="member this.WithVolumeEncryptionKeyEncryptAlgorithm : string -&gt; 'T" Usage="virtualMachineEncryptionConfiguration.WithVolumeEncryptionKeyEncryptAlgorithm encryptionAlgorithm" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionAlgorithm" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encryptionAlgorithm"><span data-ttu-id="eed7b-116">アルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="eed7b-116">The algorithm.</span></span></param>
        <summary>
             <span data-ttu-id="eed7b-117">ディスク暗号化キーの暗号化に使用するアルゴリズムを指定します。</span><span class="sxs-lookup"><span data-stu-id="eed7b-117">Specifies the algorithm used to encrypt the disk-encryption key.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-118">VirtualMachineEncryptionConfiguration です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-118">VirtualMachineEncryptionConfiguration.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithVolumeEncryptionKeyEncrypted">
      <MemberSignature Language="C#" Value="public T WithVolumeEncryptionKeyEncrypted (string keyEncryptionKeyURL);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !T WithVolumeEncryptionKeyEncrypted(string keyEncryptionKeyURL) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.WithVolumeEncryptionKeyEncrypted(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVolumeEncryptionKeyEncrypted (keyEncryptionKeyURL As String) As T" />
      <MemberSignature Language="F#" Value="member this.WithVolumeEncryptionKeyEncrypted : string -&gt; 'T" Usage="virtualMachineEncryptionConfiguration.WithVolumeEncryptionKeyEncrypted keyEncryptionKeyURL" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyEncryptionKeyURL" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyEncryptionKeyURL"><span data-ttu-id="eed7b-119">キー (KEK) の url です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-119">The key (KEK) url.</span></span></param>
        <summary>
             <span data-ttu-id="eed7b-120">キーを保護したり、ディスクの暗号化キーをラップする資格情報コンテナーの url を指定します。</span><span class="sxs-lookup"><span data-stu-id="eed7b-120">Specifies the key vault url to the key for protecting or wrapping the disk-encryption key.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-121">VirtualMachineEncryptionConfiguration です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-121">VirtualMachineEncryptionConfiguration.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithVolumeEncryptionKeyEncrypted">
      <MemberSignature Language="C#" Value="public T WithVolumeEncryptionKeyEncrypted (string keyEncryptionKeyURL, string keyEncryptionKeyKevVaultId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !T WithVolumeEncryptionKeyEncrypted(string keyEncryptionKeyURL, string keyEncryptionKeyKevVaultId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.WithVolumeEncryptionKeyEncrypted(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVolumeEncryptionKeyEncrypted (keyEncryptionKeyURL As String, keyEncryptionKeyKevVaultId As String) As T" />
      <MemberSignature Language="F#" Value="member this.WithVolumeEncryptionKeyEncrypted : string * string -&gt; 'T" Usage="virtualMachineEncryptionConfiguration.WithVolumeEncryptionKeyEncrypted (keyEncryptionKeyURL, keyEncryptionKeyKevVaultId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyEncryptionKeyURL" Type="System.String" />
        <Parameter Name="keyEncryptionKeyKevVaultId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyEncryptionKeyURL"><span data-ttu-id="eed7b-122">キー (KEK) の url です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-122">The key (KEK) url.</span></span></param>
        <param name="keyEncryptionKeyKevVaultId"><span data-ttu-id="eed7b-123">KEK を格納する keyVault のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-123">Resource id of the keyVault storing KEK.</span></span></param>
        <summary>
             <span data-ttu-id="eed7b-124">指定します、Id 資格情報コンテナーのキーと資格情報コンテナーのキーを保護したり、ディスクの暗号化キーをラップする url。</span><span class="sxs-lookup"><span data-stu-id="eed7b-124">Specifies the and key vault Id and a vault url to the key for protecting or wrapping the disk-encryption key.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-125">VirtualMachineEncryptionConfiguration です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-125">VirtualMachineEncryptionConfiguration.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithVolumeType">
      <MemberSignature Language="C#" Value="public T WithVolumeType (Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !T WithVolumeType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1.WithVolumeType(Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVolumeType (volumeType As DiskVolumeType) As T" />
      <MemberSignature Language="F#" Value="member this.WithVolumeType : Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType -&gt; 'T" Usage="virtualMachineEncryptionConfiguration.WithVolumeType volumeType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="volumeType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType" />
      </Parameters>
      <Docs>
        <param name="volumeType"><span data-ttu-id="eed7b-126">ボリュームの種類。</span><span class="sxs-lookup"><span data-stu-id="eed7b-126">The volume type.</span></span></param>
        <summary>
             <span data-ttu-id="eed7b-127">暗号化にボリュームを指定します。</span><span class="sxs-lookup"><span data-stu-id="eed7b-127">Specifies the volume to encrypt.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="eed7b-128">VirtualMachineEncryptionConfiguration です。</span><span class="sxs-lookup"><span data-stu-id="eed7b-128">VirtualMachineEncryptionConfiguration.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>