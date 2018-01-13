<Type Name="Sku" FullName="Microsoft.Azure.Management.Search.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97de1-101">価格レベルと容量を決定する、Azure Search サービスの SKU を定義する制限。</span><span class="sxs-lookup"><span data-stu-id="97de1-101">Defines the SKU of an Azure Search Service, which determines price tier and capacity limits.</span></span>
            <see href="https://azure.microsoft.com/documentation/articles/search-sku-tier/" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="97de1-102">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97de1-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SkuName&gt; name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.Sku.#ctor(System.Nullable{Microsoft.Azure.Management.Search.Models.SkuName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As Nullable(Of SkuName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.Sku : Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; -&gt; Microsoft.Azure.Management.Search.Models.Sku" Usage="new Microsoft.Azure.Management.Search.Models.Sku name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="97de1-103">検索サービスの SKU。</span><span class="sxs-lookup"><span data-stu-id="97de1-103">The SKU of the Search service.</span></span> <span data-ttu-id="97de1-104">有効な値: 'free': サービスを共有します。</span><span class="sxs-lookup"><span data-stu-id="97de1-104">Valid values include: 'free': Shared service.</span></span> <span data-ttu-id="97de1-105">'basic': 最大 3 つのレプリカを使用してサービスを専用です。</span><span class="sxs-lookup"><span data-stu-id="97de1-105">'basic': Dedicated service with up to 3 replicas.</span></span> <span data-ttu-id="97de1-106">'standard': 専用に最大 12 個のパーティションと 12 のレプリカでのサービスです。</span><span class="sxs-lookup"><span data-stu-id="97de1-106">'standard': Dedicated service with up to 12 partitions and 12 replicas.</span></span> <span data-ttu-id="97de1-107">'standard2': のような検索単位あたりの容量増加ですが standard にします。</span><span class="sxs-lookup"><span data-stu-id="97de1-107">'standard2': Similar to standard, but with more capacity per search unit.</span></span> <span data-ttu-id="97de1-108">'standard3': 最大 12 のパーティションと 12 のレプリカと (または 'highDensity' hostingMode プロパティに設定する場合より多くのインデックスとパーティション 3 つまで)、検索単位あたりの最大容量を提供します。</span><span class="sxs-lookup"><span data-stu-id="97de1-108">'standard3': Offers maximum capacity per search unit with up to 12 partitions and 12 replicas (or up to 3 partitions with more indexes if you also set the hostingMode property to 'highDensity').</span></span> <span data-ttu-id="97de1-109">使用可能な値が含まれます: '無料'、'basic'、'standard'、'standard2'、'standard3'</span><span class="sxs-lookup"><span data-stu-id="97de1-109">Possible values include: 'free', 'basic', 'standard', 'standard2', 'standard3'</span></span></param>
        <summary>
            <span data-ttu-id="97de1-110">Sku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97de1-110">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SkuName&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Nullable(Of SkuName)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97de1-111">取得または検索サービスの SKU を設定します。</span><span class="sxs-lookup"><span data-stu-id="97de1-111">Gets or sets the SKU of the Search service.</span></span> <span data-ttu-id="97de1-112">有効な値: 'free': サービスを共有します。</span><span class="sxs-lookup"><span data-stu-id="97de1-112">Valid values include: 'free': Shared service.</span></span> <span data-ttu-id="97de1-113">'basic': 最大 3 つのレプリカを使用してサービスを専用です。</span><span class="sxs-lookup"><span data-stu-id="97de1-113">'basic': Dedicated service with up to 3 replicas.</span></span> <span data-ttu-id="97de1-114">'standard': 専用に最大 12 個のパーティションと 12 のレプリカでのサービスです。</span><span class="sxs-lookup"><span data-stu-id="97de1-114">'standard': Dedicated service with up to 12 partitions and 12 replicas.</span></span> <span data-ttu-id="97de1-115">'standard2': のような検索単位あたりの容量増加ですが standard にします。</span><span class="sxs-lookup"><span data-stu-id="97de1-115">'standard2': Similar to standard, but with more capacity per search unit.</span></span> <span data-ttu-id="97de1-116">'standard3': 最大 12 のパーティションと 12 のレプリカと (または 'highDensity' hostingMode プロパティに設定する場合より多くのインデックスとパーティション 3 つまで)、検索単位あたりの最大容量を提供します。</span><span class="sxs-lookup"><span data-stu-id="97de1-116">'standard3': Offers maximum capacity per search unit with up to 12 partitions and 12 replicas (or up to 3 partitions with more indexes if you also set the hostingMode property to 'highDensity').</span></span> <span data-ttu-id="97de1-117">使用可能な値が含まれます: '無料'、'basic'、'standard'、'standard2'、'standard3'</span><span class="sxs-lookup"><span data-stu-id="97de1-117">Possible values include: 'free', 'basic', 'standard', 'standard2', 'standard3'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>