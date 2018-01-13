<Type Name="KeyVaultSecretReference" FullName="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference">
  <TypeSignature Language="C#" Value="public class KeyVaultSecretReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultSecretReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultSecretReference" />
  <TypeSignature Language="F#" Value="type KeyVaultSecretReference = class" />
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
            Key Vault のシークレットへの参照をについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.#ctor" />
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
            KeyVaultSecretReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultSecretReference (string secretUrl, Microsoft.Azure.Management.Compute.Models.SubResource sourceVault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string secretUrl, class Microsoft.Azure.Management.Compute.Models.SubResource sourceVault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.SubResource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secretUrl As String, sourceVault As SubResource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference : string * Microsoft.Azure.Management.Compute.Models.SubResource -&gt; Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference" Usage="new Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference (secretUrl, sourceVault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secretUrl" Type="System.String" />
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
      </Parameters>
      <Docs>
        <param name="secretUrl">Key Vault にシークレットを参照する URL です。</param>
        <param name="sourceVault">シークレットを含む Key Vault の相対 URL です。</param>
        <summary>
            KeyVaultSecretReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または、Key Vault にシークレットを参照する URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.SourceVault" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはシークレットを含む Key Vault の相対 URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.KeyVaultSecretReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="keyVaultSecretReference.Validate " />
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