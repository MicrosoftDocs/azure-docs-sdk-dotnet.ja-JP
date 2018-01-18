<Type Name="IntegrationRuntimeSsisCatalogInfo" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeSsisCatalogInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeSsisCatalogInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeSsisCatalogInfo" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeSsisCatalogInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e961c-101">管理対象の専用統合ランタイムのカタログ情報。</span><span class="sxs-lookup"><span data-stu-id="e961c-101">Catalog information for managed dedicated integration runtime.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeSsisCatalogInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.#ctor" />
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
            <span data-ttu-id="e961c-102">IntegrationRuntimeSsisCatalogInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e961c-102">Initializes a new instance of the IntegrationRuntimeSsisCatalogInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeSsisCatalogInfo (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string catalogServerEndpoint = null, string catalogAdminUserName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString catalogAdminPassword = null, string catalogPricingTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string catalogServerEndpoint, string catalogAdminUserName, class Microsoft.Azure.Management.DataFactory.Models.SecureString catalogAdminPassword, string catalogPricingTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional catalogServerEndpoint As String = null, Optional catalogAdminUserName As String = null, Optional catalogAdminPassword As SecureString = null, Optional catalogPricingTier As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * Microsoft.Azure.Management.DataFactory.Models.SecureString * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo (additionalProperties, catalogServerEndpoint, catalogAdminUserName, catalogAdminPassword, catalogPricingTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="catalogServerEndpoint" Type="System.String" />
        <Parameter Name="catalogAdminUserName" Type="System.String" />
        <Parameter Name="catalogAdminPassword" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="catalogPricingTier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="e961c-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="e961c-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="catalogServerEndpoint"><span data-ttu-id="e961c-104">カタログのデータベース サーバーの URL。</span><span class="sxs-lookup"><span data-stu-id="e961c-104">The catalog database server URL.</span></span></param>
        <param name="catalogAdminUserName"><span data-ttu-id="e961c-105">カタログ データベースの管理者ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="e961c-105">The administrator user name of catalog database.</span></span></param>
        <param name="catalogAdminPassword"><span data-ttu-id="e961c-106">カタログ データベースの管理者のユーザー アカウントのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="e961c-106">The password of the administrator user account of the catalog database.</span></span></param>
        <param name="catalogPricingTier"><span data-ttu-id="e961c-107">カタログ データベースの価格レベル。</span><span class="sxs-lookup"><span data-stu-id="e961c-107">The pricing tier for the catalog database.</span></span> <span data-ttu-id="e961c-108">有効な値は、https://azure.microsoft.com/en-us/pricing/details/sql-database/ で見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="e961c-108">The valid values could be found in https://azure.microsoft.com/en-us/pricing/details/sql-database/.</span></span>
            <span data-ttu-id="e961c-109">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'、'PremiumRS'</span><span class="sxs-lookup"><span data-stu-id="e961c-109">Possible values include: 'Basic', 'Standard', 'Premium', 'PremiumRS'</span></span></param>
        <summary>
            <span data-ttu-id="e961c-110">IntegrationRuntimeSsisCatalogInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e961c-110">Initializes a new instance of the IntegrationRuntimeSsisCatalogInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e961c-111">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="e961c-111">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatalogAdminPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString CatalogAdminPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString CatalogAdminPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogAdminPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property CatalogAdminPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.CatalogAdminPassword : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogAdminPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catalogAdminPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e961c-112">取得またはカタログ データベースのユーザー アカウントの管理者のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e961c-112">Gets or sets the password of the administrator user account of the catalog database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatalogAdminUserName">
      <MemberSignature Language="C#" Value="public string CatalogAdminUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CatalogAdminUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogAdminUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property CatalogAdminUserName As String" />
      <MemberSignature Language="F#" Value="member this.CatalogAdminUserName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogAdminUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catalogAdminUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e961c-113">取得またはカタログ データベースの管理者のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="e961c-113">Gets or sets the administrator user name of catalog database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatalogPricingTier">
      <MemberSignature Language="C#" Value="public string CatalogPricingTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CatalogPricingTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogPricingTier" />
      <MemberSignature Language="VB.NET" Value="Public Property CatalogPricingTier As String" />
      <MemberSignature Language="F#" Value="member this.CatalogPricingTier : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogPricingTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catalogPricingTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e961c-114">取得またはカタログ データベースの価格レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e961c-114">Gets or sets the pricing tier for the catalog database.</span></span> <span data-ttu-id="e961c-115">有効な値は、https://azure.microsoft.com/en-us/pricing/details/sql-database/ で見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="e961c-115">The valid values could be found in https://azure.microsoft.com/en-us/pricing/details/sql-database/.</span></span>
            <span data-ttu-id="e961c-116">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'、'PremiumRS'</span><span class="sxs-lookup"><span data-stu-id="e961c-116">Possible values include: 'Basic', 'Standard', 'Premium', 'PremiumRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatalogServerEndpoint">
      <MemberSignature Language="C#" Value="public string CatalogServerEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CatalogServerEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogServerEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property CatalogServerEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.CatalogServerEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.CatalogServerEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catalogServerEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e961c-117">取得またはカタログのデータベース サーバーの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="e961c-117">Gets or sets the catalog database server URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisCatalogInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="integrationRuntimeSsisCatalogInfo.Validate " />
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
            <span data-ttu-id="e961c-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e961c-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e961c-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e961c-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>