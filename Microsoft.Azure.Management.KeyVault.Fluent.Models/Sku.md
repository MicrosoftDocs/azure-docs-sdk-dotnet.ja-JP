<Type Name="Sku" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd04b-101">SKU の詳細</span><span class="sxs-lookup"><span data-stu-id="dd04b-101">SKU details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd04b-102">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dd04b-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.#ctor(Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku : Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dd04b-103">Key vault が標準的な資格情報コンテナーまたは premium のコンテナーかどうかを指定する SKU の名前です。</span><span class="sxs-lookup"><span data-stu-id="dd04b-103">SKU name to specify whether the key vault is a standard vault or a premium vault.</span></span> <span data-ttu-id="dd04b-104">使用可能な値が含まれます: 'standard'、'premium'</span><span class="sxs-lookup"><span data-stu-id="dd04b-104">Possible values include: 'standard', 'premium'</span></span></param>
        <summary>
            <span data-ttu-id="dd04b-105">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dd04b-105">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public static string Family { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Family" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd04b-106">SKU ファミリ名</span><span class="sxs-lookup"><span data-stu-id="dd04b-106">SKU family name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd04b-107">取得または、key vault が標準的な資格情報コンテナーまたは premium のコンテナーかどうかを指定する SKU 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="dd04b-107">Gets or sets SKU name to specify whether the key vault is a standard vault or a premium vault.</span></span> <span data-ttu-id="dd04b-108">使用可能な値が含まれます: 'standard'、'premium'</span><span class="sxs-lookup"><span data-stu-id="dd04b-108">Possible values include: 'standard', 'premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd04b-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="dd04b-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd04b-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd04b-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>