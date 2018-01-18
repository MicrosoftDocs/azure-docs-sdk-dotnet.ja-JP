<Type Name="RegistryUpdateParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters">
  <TypeSignature Language="C#" Value="public class RegistryUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryUpdateParameters" />
  <TypeSignature Language="F#" Value="type RegistryUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="73819-101">コンテナー レジストリを更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="73819-101">The parameters for updating a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73819-102">RegistryUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="73819-102">Initializes a new instance of the RegistryUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUpdateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku = null, Nullable&lt;bool&gt; adminUserEnabled = null, Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; adminUserEnabled, class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ContainerRegistry.Models.Sku,System.Nullable{System.Boolean},Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.Sku * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters (tags, sku, adminUserEnabled, storageAccount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
        <Parameter Name="adminUserEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="73819-103">コンテナー レジストリのタグ。</span><span class="sxs-lookup"><span data-stu-id="73819-103">The tags for the container registry.</span></span></param>
        <param name="sku"><span data-ttu-id="73819-104">コンテナー レジストリの SKU。</span><span class="sxs-lookup"><span data-stu-id="73819-104">The SKU of the container registry.</span></span></param>
        <param name="adminUserEnabled"><span data-ttu-id="73819-105">管理者ユーザーが有効になっているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="73819-105">The value that indicates whether the admin user is enabled.</span></span></param>
        <param name="storageAccount"><span data-ttu-id="73819-106">コンテナー レジストリのストレージ アカウントのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="73819-106">The parameters of a storage account for the container registry.</span></span> <span data-ttu-id="73819-107">従来の SKU にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="73819-107">Only applicable to Classic SKU.</span></span> <span data-ttu-id="73819-108">指定した場合、ストレージ アカウント コンテナー レジストリと同じ物理的な場所にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="73819-108">If specified, the storage account must be in the same physical location as the container registry.</span></span></param>
        <summary>
            <span data-ttu-id="73819-109">RegistryUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="73819-109">Initializes a new instance of the RegistryUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdminUserEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdminUserEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.AdminUserEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdminUserEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.AdminUserEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminUserEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73819-110">取得または管理ユーザーが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="73819-110">Gets or sets the value that indicates whether the admin user is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ContainerRegistry.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73819-111">取得またはコンテナー レジストリの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="73819-111">Gets or sets the SKU of the container registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccountProperties" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73819-112">取得またはコンテナー レジストリのストレージ アカウントのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="73819-112">Gets or sets the parameters of a storage account for the container registry.</span></span> <span data-ttu-id="73819-113">従来の SKU にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="73819-113">Only applicable to Classic SKU.</span></span> <span data-ttu-id="73819-114">指定した場合、ストレージ アカウント コンテナー レジストリと同じ物理的な場所にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="73819-114">If specified, the storage account must be in the same physical location as the container registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
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
            <span data-ttu-id="73819-115">取得またはコンテナー レジストリにタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="73819-115">Gets or sets the tags for the container registry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="registryUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73819-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="73819-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="73819-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="73819-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>