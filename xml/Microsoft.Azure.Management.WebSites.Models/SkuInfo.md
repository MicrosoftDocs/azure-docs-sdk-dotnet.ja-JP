<Type Name="SkuInfo" FullName="Microsoft.Azure.Management.WebSites.Models.SkuInfo">
  <TypeSignature Language="C#" Value="public class SkuInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SkuInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SkuInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class SkuInfo" />
  <TypeSignature Language="F#" Value="type SkuInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45108-101">SKU の検出情報です。</span><span class="sxs-lookup"><span data-stu-id="45108-101">SKU discovery information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45108-102">SkuInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45108-102">Initializes a new instance of the SkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfo (string resourceType = null, Microsoft.Azure.Management.WebSites.Models.SkuDescription sku = null, Microsoft.Azure.Management.WebSites.Models.SkuCapacity capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class Microsoft.Azure.Management.WebSites.Models.SkuDescription sku, class Microsoft.Azure.Management.WebSites.Models.SkuCapacity capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuInfo.#ctor(System.String,Microsoft.Azure.Management.WebSites.Models.SkuDescription,Microsoft.Azure.Management.WebSites.Models.SkuCapacity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional sku As SkuDescription = null, Optional capacity As SkuCapacity = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SkuInfo : string * Microsoft.Azure.Management.WebSites.Models.SkuDescription * Microsoft.Azure.Management.WebSites.Models.SkuCapacity -&gt; Microsoft.Azure.Management.WebSites.Models.SkuInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.SkuInfo (resourceType, sku, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.WebSites.Models.SkuCapacity" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="45108-103">この SKU が適用されるリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="45108-103">Resource type that this SKU applies to.</span></span></param>
        <param name="sku"><span data-ttu-id="45108-104">名前と、SKU の層です。</span><span class="sxs-lookup"><span data-stu-id="45108-104">Name and tier of the SKU.</span></span></param>
        <param name="capacity"><span data-ttu-id="45108-105">Min、max、および SKU の既定の小数点以下桁数の値。</span><span class="sxs-lookup"><span data-stu-id="45108-105">Min, max, and default scale values of the SKU.</span></span></param>
        <summary>
            <span data-ttu-id="45108-106">SkuInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45108-106">Initializes a new instance of the SkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As SkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.WebSites.Models.SkuCapacity with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45108-107">取得または min、max、および SKU の既定の小数点以下桁数の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="45108-107">Gets or sets min, max, and default scale values of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45108-108">取得またはこの SKU が適用されるリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="45108-108">Gets or sets resource type that this SKU applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.WebSites.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45108-109">取得または設定の名前と、SKU のレベル。</span><span class="sxs-lookup"><span data-stu-id="45108-109">Gets or sets name and tier of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>