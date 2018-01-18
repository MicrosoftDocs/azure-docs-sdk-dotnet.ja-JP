<Type Name="ResourceNameAvailabilityRequest" FullName="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest">
  <TypeSignature Language="C#" Value="public class ResourceNameAvailabilityRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceNameAvailabilityRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceNameAvailabilityRequest" />
  <TypeSignature Language="F#" Value="type ResourceNameAvailabilityRequest = class" />
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
            <span data-ttu-id="3fe5c-101">リソースの名前の可用性要求の内容。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-101">Resource name availability request content.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailabilityRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3fe5c-102">ResourceNameAvailabilityRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-102">Initializes a new instance of the ResourceNameAvailabilityRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailabilityRequest (string name, string type, Nullable&lt;bool&gt; isFqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.#ctor(System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As String, Optional isFqdn As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest : string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest (name, type, isFqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3fe5c-103">リソース名を確認してください。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-103">Resource name to verify.</span></span></param>
        <param name="type"><span data-ttu-id="3fe5c-104">リソースの種類の検証に使用します。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-104">Resource type used for verification.</span></span> <span data-ttu-id="3fe5c-105">使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'</span><span class="sxs-lookup"><span data-stu-id="3fe5c-105">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span></param>
        <param name="isFqdn"><span data-ttu-id="3fe5c-106">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-106">Is fully qualified domain name.</span></span></param>
        <summary>
            <span data-ttu-id="3fe5c-107">ResourceNameAvailabilityRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-107">Initializes a new instance of the ResourceNameAvailabilityRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFqdn">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.IsFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property IsFqdn As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsFqdn : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.IsFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe5c-108">取得または設定は、完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-108">Gets or sets is fully qualified domain name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe5c-109">取得または設定を確認するリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-109">Gets or sets resource name to verify.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fe5c-110">取得または設定の検証に使用するリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-110">Gets or sets resource type used for verification.</span></span> <span data-ttu-id="3fe5c-111">使用可能な値が含まれます: 'サイト'、'スロット'、'HostingEnvironment'</span><span class="sxs-lookup"><span data-stu-id="3fe5c-111">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailabilityRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceNameAvailabilityRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3fe5c-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3fe5c-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3fe5c-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>