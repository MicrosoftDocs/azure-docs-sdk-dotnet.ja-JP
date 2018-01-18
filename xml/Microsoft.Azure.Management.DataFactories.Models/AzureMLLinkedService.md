<Type Name="AzureMLLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMLLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureML")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4412b-101">Azure ML Web サービスにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="4412b-101">Azure ML Web Service linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4412b-102">AzureMLLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4412b-102">Initializes a new instance of the AzureMLLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService (string mlEndpoint, string apiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mlEndpoint, string apiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mlEndpoint As String, apiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService (mlEndpoint, apiKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mlEndpoint" Type="System.String" />
        <Parameter Name="apiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mlEndpoint">To be added.</param>
        <param name="apiKey">To be added.</param>
        <summary>
            <span data-ttu-id="4412b-103">必須の引数で AzureMLLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4412b-103">Initializes a new instance of the AzureMLLinkedService class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-104">必須。</span><span class="sxs-lookup"><span data-stu-id="4412b-104">Required.</span></span> <span data-ttu-id="4412b-105">Azure ML モデル エンドポイントにアクセスするために API キー。</span><span class="sxs-lookup"><span data-stu-id="4412b-105">The API key for accessing the Azure ML model endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MlEndpoint">
      <MemberSignature Language="C#" Value="public string MlEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MlEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MlEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.MlEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-106">必須。</span><span class="sxs-lookup"><span data-stu-id="4412b-106">Required.</span></span> <span data-ttu-id="4412b-107">Azure ML Web サービス エンドポイントのバッチ実行 REST の URL です。</span><span class="sxs-lookup"><span data-stu-id="4412b-107">The Batch Execution REST URL for an Azure ML Web Service endpoint.</span></span>
            <span data-ttu-id="4412b-108">エンドポイントの形式を使用する必要があります: https://_地域_.services.azureml.net/workspaces/_workspace_id_/services/_service_id_ジョブ/? api バージョン = 2.0"</span><span class="sxs-lookup"><span data-stu-id="4412b-108">The endpoint should be of the form: https://_region_.services.azureml.net/workspaces/_workspace_id_/services/_service_id_/jobs?api-version=2.0"</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4412b-109">Optional.</span></span> <span data-ttu-id="4412b-110">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルの ID。</span><span class="sxs-lookup"><span data-stu-id="4412b-110">The ID of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public string ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4412b-111">Optional.</span></span> <span data-ttu-id="4412b-112">Azure ML web サービスの ARM ベース updateResourceEndpoint に対する認証に使用されるサービス プリンシパルのキー。</span><span class="sxs-lookup"><span data-stu-id="4412b-112">The key of the service principal used to authenticate against the ARM-based updateResourceEndpoint of an Azure ML web service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public string Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As String" />
      <MemberSignature Language="F#" Value="member this.Tenant : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4412b-113">Optional.</span></span> <span data-ttu-id="4412b-114">名前またはサービス プリンシパルが属しているテナントの ID。</span><span class="sxs-lookup"><span data-stu-id="4412b-114">The name or ID of the tenant to which the service principal belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateResourceEndpoint">
      <MemberSignature Language="C#" Value="public string UpdateResourceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateResourceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateResourceEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.UpdateResourceEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4412b-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4412b-115">Optional.</span></span> <span data-ttu-id="4412b-116">Azure ML Web サービス エンドポイントの更新リソース REST の URL。</span><span class="sxs-lookup"><span data-stu-id="4412b-116">The Update Resource REST URL for an Azure ML Web Service endpoint.</span></span>
            <span data-ttu-id="4412b-117">エンドポイントの形式を使用する必要があります: https://management.azureml.net/workspaces/_workspace_id_/webservices/_service_id_/endpoints/_endpointName_です。</span><span class="sxs-lookup"><span data-stu-id="4412b-117">The endpoint should be of the form: https://management.azureml.net/workspaces/_workspace_id_/webservices/_service_id_/endpoints/_endpointName_.</span></span>
            <span data-ttu-id="4412b-118">このプロパティを使用して再トレーニング後で、エンドポイントを更新して<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" />です。</span><span class="sxs-lookup"><span data-stu-id="4412b-118">Include this property for updating the endpoint after retraining, using <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>