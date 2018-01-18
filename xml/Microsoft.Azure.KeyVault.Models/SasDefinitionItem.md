<Type Name="SasDefinitionItem" FullName="Microsoft.Azure.KeyVault.Models.SasDefinitionItem">
  <TypeSignature Language="C#" Value="public class SasDefinitionItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasDefinitionItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SasDefinitionItem" />
  <TypeSignature Language="VB.NET" Value="Public Class SasDefinitionItem" />
  <TypeSignature Language="F#" Value="type SasDefinitionItem = class" />
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
            <span data-ttu-id="93d6c-101">記憶域の SAS の定義は、ストレージの SAS 定義メタデータを含む項目です。</span><span class="sxs-lookup"><span data-stu-id="93d6c-101">The storage SAS definition item containing storage SAS definition metadata.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="93d6c-102">SasDefinitionItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-102">Initializes a new instance of the SasDefinitionItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionItem (string id = null, string secretId = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string secretId, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional secretId As String = null, Optional attributes As SasDefinitionAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SasDefinitionItem : string * string * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.SasDefinitionItem" Usage="new Microsoft.Azure.KeyVault.Models.SasDefinitionItem (id, secretId, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="secretId" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="93d6c-103">ストレージの SAS 識別子です。</span><span class="sxs-lookup"><span data-stu-id="93d6c-103">The storage SAS identifier.</span></span></param>
        <param name="secretId"><span data-ttu-id="93d6c-104">記憶域アカウント SAS 定義シークレット id です。</span><span class="sxs-lookup"><span data-stu-id="93d6c-104">The storage account SAS definition secret id.</span></span></param>
        <param name="attributes"><span data-ttu-id="93d6c-105">SAS 定義管理属性。</span><span class="sxs-lookup"><span data-stu-id="93d6c-105">The SAS definition management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="93d6c-106">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="93d6c-106">Application specific metadata in the form of key-value pairs.</span></span></param>
        <summary>
            <span data-ttu-id="93d6c-107">SasDefinitionItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-107">Initializes a new instance of the SasDefinitionItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Attributes As SasDefinitionAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Attributes" />
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
            <span data-ttu-id="93d6c-108">SAS 定義管理属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-108">Gets the SAS definition management attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Id" />
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
            <span data-ttu-id="93d6c-109">ストレージの SAS 識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-109">Gets the storage SAS identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.SasDefinitionIdentifier Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.SasDefinitionIdentifier Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As SasDefinitionIdentifier" />
      <MemberSignature Language="F#" Value="member this.Identifier : Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.SasDefinitionIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93d6c-110">記憶域 SAS の資格情報コンテナー定義識別子です。</span><span class="sxs-lookup"><span data-stu-id="93d6c-110">The key vault storage SAS definition identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretId">
      <MemberSignature Language="C#" Value="public string SecretId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.SecretId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretId As String" />
      <MemberSignature Language="F#" Value="member this.SecretId : string" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.SecretId" />
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
            <span data-ttu-id="93d6c-111">記憶域アカウント SAS の定義のシークレット id を取得します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-111">Gets the storage account SAS definition secret id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionItem.Tags" />
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
            <span data-ttu-id="93d6c-112">キー/値ペアの形式でのアプリケーション固有のメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="93d6c-112">Gets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>