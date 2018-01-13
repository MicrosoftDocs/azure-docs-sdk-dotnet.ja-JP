<Type Name="KeyVaultAndSecretReference" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference">
  <TypeSignature Language="C#" Value="public class KeyVaultAndSecretReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultAndSecretReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultAndSecretReference" />
  <TypeSignature Language="F#" Value="type KeyVaultAndSecretReference = class" />
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
            <span data-ttu-id="2d965-101">暗号化キーの Key Vault シークレットの Url と資格情報コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="2d965-101">Key Vault Secret Url and vault id of the encryption key</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndSecretReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d965-102">KeyVaultAndSecretReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d965-102">Initializes a new instance of the KeyVaultAndSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndSecretReference (Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault sourceVault, string secretUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault sourceVault, string secretUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference : Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference (sourceVault, secretUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault" />
        <Parameter Name="secretUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="2d965-103">キーまたはシークレットを含む KeyVault リソース id</span><span class="sxs-lookup"><span data-stu-id="2d965-103">Resource id of the KeyVault containing the key or secret</span></span></param>
        <param name="secretUrl"><span data-ttu-id="2d965-104">キーやシークレット KeyVault を指す Url</span><span class="sxs-lookup"><span data-stu-id="2d965-104">Url pointing to a key or secret in KeyVault</span></span></param>
        <summary>
            <span data-ttu-id="2d965-105">KeyVaultAndSecretReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d965-105">Initializes a new instance of the KeyVaultAndSecretReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d965-106">取得または設定キーやシークレット KeyVault を指す url</span><span class="sxs-lookup"><span data-stu-id="2d965-106">Gets or sets url pointing to a key or secret in KeyVault</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SourceVault" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.SourceVault</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d965-107">取得または設定のキーまたはシークレットを含む KeyVault リソース id</span><span class="sxs-lookup"><span data-stu-id="2d965-107">Gets or sets resource id of the KeyVault containing the key or secret</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultAndSecretReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d965-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2d965-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2d965-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d965-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>