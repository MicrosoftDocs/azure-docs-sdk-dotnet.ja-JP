<Type Name="Location" FullName="Microsoft.Azure.Management.ResourceManager.Models.Location">
  <TypeSignature Language="C#" Value="public class Location" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Location extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.Location" />
  <TypeSignature Language="VB.NET" Value="Public Class Location" />
  <TypeSignature Language="F#" Value="type Location = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="639e3-101">場所情報です。</span><span class="sxs-lookup"><span data-stu-id="639e3-101">Location information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Location ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Location.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="639e3-102">Location クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="639e3-102">Initializes a new instance of the Location class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Location (string id = null, string subscriptionId = null, string name = null, string displayName = null, string latitude = null, string longitude = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string subscriptionId, string name, string displayName, string latitude, string longitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Location.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional subscriptionId As String = null, Optional name As String = null, Optional displayName As String = null, Optional latitude As String = null, Optional longitude As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.Location : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Location" Usage="new Microsoft.Azure.Management.ResourceManager.Models.Location (id, subscriptionId, name, displayName, latitude, longitude)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="latitude" Type="System.String" />
        <Parameter Name="longitude" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="639e3-103">場所の完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="639e3-103">The fully qualified ID of the location.</span></span> <span data-ttu-id="639e3-104">たとえば、サブスクリプション/00000000-0000-0000-0000-000000000000/場所/westus です。</span><span class="sxs-lookup"><span data-stu-id="639e3-104">For example, /subscriptions/00000000-0000-0000-0000-000000000000/locations/westus.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="639e3-105">サブスクリプション id。</span><span class="sxs-lookup"><span data-stu-id="639e3-105">The subscription ID.</span></span></param>
        <param name="name"><span data-ttu-id="639e3-106">場所の名前。</span><span class="sxs-lookup"><span data-stu-id="639e3-106">The location name.</span></span></param>
        <param name="displayName"><span data-ttu-id="639e3-107">場所の表示名。</span><span class="sxs-lookup"><span data-stu-id="639e3-107">The display name of the location.</span></span></param>
        <param name="latitude"><span data-ttu-id="639e3-108">場所の緯度です。</span><span class="sxs-lookup"><span data-stu-id="639e3-108">The latitude of the location.</span></span></param>
        <param name="longitude"><span data-ttu-id="639e3-109">場所の経度です。</span><span class="sxs-lookup"><span data-stu-id="639e3-109">The longitude of the location.</span></span></param>
        <summary>
            <span data-ttu-id="639e3-110">Location クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="639e3-110">Initializes a new instance of the Location class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="639e3-111">場所の表示名を取得します。</span><span class="sxs-lookup"><span data-stu-id="639e3-111">Gets the display name of the location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="639e3-112">場所の完全修飾 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="639e3-112">Gets the fully qualified ID of the location.</span></span> <span data-ttu-id="639e3-113">たとえば、サブスクリプション/00000000-0000-0000-0000-000000000000/場所/westus です。</span><span class="sxs-lookup"><span data-stu-id="639e3-113">For example, /subscriptions/00000000-0000-0000-0000-000000000000/locations/westus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Latitude">
      <MemberSignature Language="C#" Value="public string Latitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Latitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.Latitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Latitude As String" />
      <MemberSignature Language="F#" Value="member this.Latitude : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.Latitude" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="latitude")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="639e3-114">場所の緯度を取得します。</span><span class="sxs-lookup"><span data-stu-id="639e3-114">Gets the latitude of the location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Longitude">
      <MemberSignature Language="C#" Value="public string Longitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Longitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.Longitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Longitude As String" />
      <MemberSignature Language="F#" Value="member this.Longitude : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.Longitude" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="longitude")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="639e3-115">場所の経度を取得します。</span><span class="sxs-lookup"><span data-stu-id="639e3-115">Gets the longitude of the location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
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
            <span data-ttu-id="639e3-116">場所の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="639e3-116">Gets the location name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Location.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Location.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="639e3-117">サブスクリプション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="639e3-117">Gets the subscription ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>