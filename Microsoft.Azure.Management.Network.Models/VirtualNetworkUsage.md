<Type Name="VirtualNetworkUsage" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage">
  <TypeSignature Language="C#" Value="public class VirtualNetworkUsage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkUsage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkUsage" />
  <TypeSignature Language="F#" Value="type VirtualNetworkUsage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cb050-101">サブネットの使用方法の詳細。</span><span class="sxs-lookup"><span data-stu-id="cb050-101">Usage details for subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cb050-102">VirtualNetworkUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cb050-102">Initializes a new instance of the VirtualNetworkUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkUsage (Nullable&lt;double&gt; currentValue = null, string id = null, Nullable&lt;double&gt; limit = null, Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName name = null, string unit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;float64&gt; currentValue, string id, valuetype System.Nullable`1&lt;float64&gt; limit, class Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName name, string unit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.#ctor(System.Nullable{System.Double},System.String,System.Nullable{System.Double},Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional currentValue As Nullable(Of Double) = null, Optional id As String = null, Optional limit As Nullable(Of Double) = null, Optional name As VirtualNetworkUsageName = null, Optional unit As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage : Nullable&lt;double&gt; * string * Nullable&lt;double&gt; * Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage (currentValue, id, limit, name, unit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName" />
        <Parameter Name="unit" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="currentValue"><span data-ttu-id="cb050-103">サブネットから使用される Ip の数を示します。</span><span class="sxs-lookup"><span data-stu-id="cb050-103">Indicates number of IPs used from the Subnet.</span></span></param>
        <param name="id"><span data-ttu-id="cb050-104">サブネットの識別子です。</span><span class="sxs-lookup"><span data-stu-id="cb050-104">Subnet identifier.</span></span></param>
        <param name="limit"><span data-ttu-id="cb050-105">サブネットのサイズを示します。</span><span class="sxs-lookup"><span data-stu-id="cb050-105">Indicates the size of the subnet.</span></span></param>
        <param name="name"><span data-ttu-id="cb050-106">使用状況の一般的なとローカライズされた値を表す名前です。</span><span class="sxs-lookup"><span data-stu-id="cb050-106">The name containing common and localized value for usage.</span></span></param>
        <param name="unit"><span data-ttu-id="cb050-107">使用状況の単位です。</span><span class="sxs-lookup"><span data-stu-id="cb050-107">Usage units.</span></span> <span data-ttu-id="cb050-108">'Count' を返します。</span><span class="sxs-lookup"><span data-stu-id="cb050-108">Returns 'Count'</span></span></param>
        <summary>
            <span data-ttu-id="cb050-109">VirtualNetworkUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cb050-109">Initializes a new instance of the VirtualNetworkUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb050-110">取得では、Ip サブネットから使用の数を示します。</span><span class="sxs-lookup"><span data-stu-id="cb050-110">Gets indicates number of IPs used from the Subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="cb050-111">サブネットの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="cb050-111">Gets subnet identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb050-112">取得では、サブネットのサイズを示します。</span><span class="sxs-lookup"><span data-stu-id="cb050-112">Gets indicates the size of the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As VirtualNetworkUsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkUsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb050-113">使用状況の一般的なとローカライズされた値を表す名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="cb050-113">Gets the name containing common and localized value for usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cb050-114">使用状況のユニットを取得します。</span><span class="sxs-lookup"><span data-stu-id="cb050-114">Gets usage units.</span></span> <span data-ttu-id="cb050-115">'Count' を返します。</span><span class="sxs-lookup"><span data-stu-id="cb050-115">Returns 'Count'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>