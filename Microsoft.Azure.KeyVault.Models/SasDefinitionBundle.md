<Type Name="SasDefinitionBundle" FullName="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle">
  <TypeSignature Language="C#" Value="public class SasDefinitionBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasDefinitionBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class SasDefinitionBundle" />
  <TypeSignature Language="F#" Value="type SasDefinitionBundle = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e536-101">SAS 定義バンドルは、資格情報コンテナーの SAS 定義の詳細とその属性で構成されます。</span><span class="sxs-lookup"><span data-stu-id="1e536-101">A SAS definition bundle consists of key vault SAS definition details plus its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e536-102">SasDefinitionBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e536-102">Initializes a new instance of the SasDefinitionBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionBundle (string id = null, string secretId = null, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string secretId, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.#ctor(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional secretId As String = null, Optional parameters As IDictionary(Of String, String) = null, Optional attributes As SasDefinitionAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SasDefinitionBundle : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.SasDefinitionBundle" Usage="new Microsoft.Azure.KeyVault.Models.SasDefinitionBundle (id, secretId, parameters, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="secretId" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1e536-103">SAS 定義 id。</span><span class="sxs-lookup"><span data-stu-id="1e536-103">The SAS definition id.</span></span></param>
        <param name="secretId"><span data-ttu-id="1e536-104">記憶域アカウント SAS 定義シークレット id です。</span><span class="sxs-lookup"><span data-stu-id="1e536-104">Storage account SAS definition secret id.</span></span></param>
        <param name="parameters"><span data-ttu-id="1e536-105">キー/値ペアの形式で SAS 定義のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1e536-105">The SAS definition metadata in the form of key-value pairs.</span></span></param>
        <param name="attributes"><span data-ttu-id="1e536-106">SAS 定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="1e536-106">The SAS definition attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="1e536-107">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="1e536-107">Application specific metadata in the form of key-value pairs</span></span></param>
        <summary>
            <span data-ttu-id="1e536-108">SasDefinitionBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e536-108">Initializes a new instance of the SasDefinitionBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Attributes As SasDefinitionAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e536-109">SAS の定義の属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="1e536-109">Gets the SAS definition attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e536-110">SAS 定義 id を取得します。</span><span class="sxs-lookup"><span data-stu-id="1e536-110">Gets the SAS definition id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e536-111">キー/値ペアの形式で、SAS 定義のメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="1e536-111">Gets the SAS definition metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretId">
      <MemberSignature Language="C#" Value="public string SecretId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.SecretId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretId As String" />
      <MemberSignature Language="F#" Value="member this.SecretId : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.SecretId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e536-112">記憶域アカウント SAS 定義シークレット id を取得します。</span><span class="sxs-lookup"><span data-stu-id="1e536-112">Gets storage account SAS definition secret id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionBundle.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e536-113">キー/値ペアの形式でのアプリケーション固有のメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="1e536-113">Gets application specific metadata in the form of key-value pairs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>