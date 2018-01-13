<Type Name="SasDefinitionCreateParameters" FullName="Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters">
  <TypeSignature Language="C#" Value="public class SasDefinitionCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasDefinitionCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SasDefinitionCreateParameters" />
  <TypeSignature Language="F#" Value="type SasDefinitionCreateParameters = class" />
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
            <span data-ttu-id="fcea7-101">SAS の定義は、パラメーターを作成します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-101">The SAS definition create parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcea7-102">SasDefinitionCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-102">Initializes a new instance of the SasDefinitionCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionCreateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters" Usage="new Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters (parameters, sasDefinitionAttributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="fcea7-103">Sas 定義は、キー/値ペアの形式でのメタデータを作成します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-103">Sas definition creation metadata in the form of key-value pairs.</span></span></param>
        <param name="sasDefinitionAttributes"><span data-ttu-id="fcea7-104">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="fcea7-104">The attributes of the SAS definition.</span></span></param>
        <param name="tags"><span data-ttu-id="fcea7-105">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="fcea7-105">Application specific metadata in the form of key-value pairs.</span></span></param>
        <summary>
            <span data-ttu-id="fcea7-106">SasDefinitionCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-106">Initializes a new instance of the SasDefinitionCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.Parameters" />
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
            <span data-ttu-id="fcea7-107">取得またはキー/値ペアの形式で sas 定義の作成のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-107">Gets or sets sas definition creation metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasDefinitionAttributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes SasDefinitionAttributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes SasDefinitionAttributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.SasDefinitionAttributes" />
      <MemberSignature Language="VB.NET" Value="Public Property SasDefinitionAttributes As SasDefinitionAttributes" />
      <MemberSignature Language="F#" Value="member this.SasDefinitionAttributes : Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.SasDefinitionAttributes" />
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
            <span data-ttu-id="fcea7-108">取得または SAS 定義の属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-108">Gets or sets the attributes of the SAS definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.Tags" />
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
            <span data-ttu-id="fcea7-109">取得またはキー/値ペアの形式でアプリケーション固有のメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-109">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SasDefinitionCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sasDefinitionCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcea7-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fcea7-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fcea7-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fcea7-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>