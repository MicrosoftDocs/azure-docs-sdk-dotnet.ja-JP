<Type Name="KeyVaultAndKeyReference" FullName="Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference">
  <TypeSignature Language="C#" Value="public class KeyVaultAndKeyReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultAndKeyReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultAndKeyReference" />
  <TypeSignature Language="F#" Value="type KeyVaultAndKeyReference = class" />
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
            <span data-ttu-id="0496a-101">Key Vault のキー Url KeK の資格情報コンテナーの id は、KeK は省略可能な暗号化キーのラップを解除するために使用が提供されている場合、</span><span class="sxs-lookup"><span data-stu-id="0496a-101">Key Vault Key Url and vault id of KeK, KeK is optional and when provided is used to unwrap the encryptionKey</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndKeyReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.#ctor" />
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
            <span data-ttu-id="0496a-102">KeyVaultAndKeyReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0496a-102">Initializes a new instance of the KeyVaultAndKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultAndKeyReference (Microsoft.Azure.Management.Compute.Models.SourceVault sourceVault, string keyUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.SourceVault sourceVault, string keyUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.#ctor(Microsoft.Azure.Management.Compute.Models.SourceVault,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference : Microsoft.Azure.Management.Compute.Models.SourceVault * string -&gt; Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference" Usage="new Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference (sourceVault, keyUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.Compute.Models.SourceVault" />
        <Parameter Name="keyUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="0496a-103">キーまたはシークレットを含む KeyVault リソース id</span><span class="sxs-lookup"><span data-stu-id="0496a-103">Resource id of the KeyVault containing the key or secret</span></span></param>
        <param name="keyUrl"><span data-ttu-id="0496a-104">キーやシークレット KeyVault を指す Url</span><span class="sxs-lookup"><span data-stu-id="0496a-104">Url pointing to a key or secret in KeyVault</span></span></param>
        <summary>
            <span data-ttu-id="0496a-105">KeyVaultAndKeyReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0496a-105">Initializes a new instance of the KeyVaultAndKeyReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0496a-106">取得または設定キーやシークレット KeyVault を指す url</span><span class="sxs-lookup"><span data-stu-id="0496a-106">Gets or sets url pointing to a key or secret in KeyVault</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SourceVault SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SourceVault SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SourceVault" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.Compute.Models.SourceVault with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SourceVault</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0496a-107">取得または設定のキーまたはシークレットを含む KeyVault リソース id</span><span class="sxs-lookup"><span data-stu-id="0496a-107">Gets or sets resource id of the KeyVault containing the key or secret</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultAndKeyReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0496a-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0496a-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0496a-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0496a-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>