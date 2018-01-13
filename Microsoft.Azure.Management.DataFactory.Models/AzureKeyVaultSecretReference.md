<Type Name="AzureKeyVaultSecretReference" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference">
  <TypeSignature Language="C#" Value="public class AzureKeyVaultSecretReference : Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureKeyVaultSecretReference extends Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureKeyVaultSecretReference&#xA;Inherits SecretBase" />
  <TypeSignature Language="F#" Value="type AzureKeyVaultSecretReference = class&#xA;    inherit SecretBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultReference</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.DataFactory.Models.SecretBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureKeyVaultSecret")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Key Vault シークレットの参照です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureKeyVaultSecretReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureKeyVaultSecretReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureKeyVaultSecretReference (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference store, object secretName, object secretVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference store, object secretName, object secretVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (store As LinkedServiceReference, secretName As Object, Optional secretVersion As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference (store, secretName, secretVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="secretName" Type="System.Object" />
        <Parameter Name="secretVersion" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="store">Azure Key Vault には、サービス参照の追加がリンクされています。</param>
        <param name="secretName">Azure Key Vault にシークレットの名前。
            型: 文字列 (または式の resultType 文字列)。</param>
        <param name="secretVersion">Azure Key Vault にシークレットのバージョン。 既定値は、最新バージョンのシークレットです。 型: 文字列 (または式の resultType 文字列)。</param>
        <summary>
            AzureKeyVaultSecretReference クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretName">
      <MemberSignature Language="C#" Value="public object SecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.SecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretName As Object" />
      <MemberSignature Language="F#" Value="member this.SecretName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.SecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Key Vault にシークレットの名前を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretVersion">
      <MemberSignature Language="C#" Value="public object SecretVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SecretVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.SecretVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretVersion As Object" />
      <MemberSignature Language="F#" Value="member this.SecretVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.SecretVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Key Vault にシークレットのバージョンを設定します。 既定値は、最新バージョンのシークレットです。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Store">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference Store { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference Store" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.Store" />
      <MemberSignature Language="VB.NET" Value="Public Property Store As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.Store : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.Store" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="store")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリンクされている Azure Key Vault サービス参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureKeyVaultSecretReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureKeyVaultSecretReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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