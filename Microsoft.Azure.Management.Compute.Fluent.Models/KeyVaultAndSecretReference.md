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
            暗号化キーの Key Vault シークレットの Url と資格情報コンテナーの id
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
            KeyVaultAndSecretReference クラスの新しいインスタンスを初期化します。
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
        <param name="sourceVault">キーまたはシークレットを含む KeyVault リソース id</param>
        <param name="secretUrl">キーやシークレット KeyVault を指す Url</param>
        <summary>
            KeyVaultAndSecretReference クラスの新しいインスタンスを初期化します。
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
            取得または設定キーやシークレット KeyVault を指す url
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
            取得または設定のキーまたはシークレットを含む KeyVault リソース id
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>