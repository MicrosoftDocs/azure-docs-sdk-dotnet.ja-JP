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
             仮想マシンに適用されるを表すの暗号化構成を入力します。
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
        <param name="keyVaultId">ディスクの暗号化キーを格納する key vault のリソース id です。</param>
        <param name="aadClientId">Key vault にアクセスするには、アプリケーション クライアント id を AAD です。</param>
        <param name="aadSecret">Key vault にアクセスする AAD アプリケーション クライアント シークレット。</param>
        <summary>
             VirtualMachineEncryptionConfiguration を作成します。
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
        <return>Key vault にアクセスする AAD アプリケーション クライアント id。</return>
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
        <return>Key vault にアクセスする AAD アプリケーション クライアント シークレット。</return>
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
        <return>キー (KEK) を保護するキーの資格情報コンテナーの url (暗号化)、ディスクの暗号化キー。</return>
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
        <return>キーの暗号化キー (KEK) を保持する key vault のリソース id です。</return>
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
        <return>ディスクの暗号化キーを格納する key vault のリソース id です。</return>
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
        <return>ディスクの暗号化キーを格納する、key vault の Url。</return>
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
        <return>Linux OS とデータ ディスクを暗号化するパスフレーズです。</return>
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
        <return>オペレーティング システムの種類。</return>
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
        <return>ディスク暗号化キーの暗号化に使用されるアルゴリズム。</return>
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
        <return>暗号化操作を実行するボリュームの種類です。</return>
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
        <param name="encryptionAlgorithm">アルゴリズム。</param>
        <summary>
             ディスク暗号化キーの暗号化に使用するアルゴリズムを指定します。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VirtualMachineEncryptionConfiguration です。</return>
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
        <param name="keyEncryptionKeyURL">キー (KEK) の url です。</param>
        <summary>
             キーを保護したり、ディスクの暗号化キーをラップする資格情報コンテナーの url を指定します。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VirtualMachineEncryptionConfiguration です。</return>
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
        <param name="keyEncryptionKeyURL">キー (KEK) の url です。</param>
        <param name="keyEncryptionKeyKevVaultId">KEK を格納する keyVault のリソース id です。</param>
        <summary>
             指定します、Id 資格情報コンテナーのキーと資格情報コンテナーのキーを保護したり、ディスクの暗号化キーをラップする url。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VirtualMachineEncryptionConfiguration です。</return>
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
        <param name="volumeType">ボリュームの種類。</param>
        <summary>
             暗号化にボリュームを指定します。
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>VirtualMachineEncryptionConfiguration です。</return>
      </Docs>
    </Member>
  </Members>
</Type>