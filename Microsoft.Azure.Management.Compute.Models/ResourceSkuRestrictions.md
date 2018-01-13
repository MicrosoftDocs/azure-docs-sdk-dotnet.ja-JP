<Type Name="ResourceSkuRestrictions" FullName="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions">
  <TypeSignature Language="C#" Value="public class ResourceSkuRestrictions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceSkuRestrictions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceSkuRestrictions" />
  <TypeSignature Language="F#" Value="type ResourceSkuRestrictions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13a06-101">SKU の拡大縮小に関する情報をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="13a06-101">Describes scaling information of a SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuRestrictions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13a06-102">ResourceSkuRestrictions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13a06-102">Initializes a new instance of the ResourceSkuRestrictions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuRestrictions (Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt; type = null, System.Collections.Generic.IList&lt;string&gt; values = null, Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo restrictionInfo = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt; reasonCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt; type, class System.Collections.Generic.IList`1&lt;string&gt; values, class Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo restrictionInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt; reasonCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo,System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As Nullable(Of ResourceSkuRestrictionsType) = null, Optional values As IList(Of String) = null, Optional restrictionInfo As ResourceSkuRestrictionInfo = null, Optional reasonCode As Nullable(Of ResourceSkuRestrictionsReasonCode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions" Usage="new Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions (type, values, restrictionInfo, reasonCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt;" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="restrictionInfo" Type="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo" />
        <Parameter Name="reasonCode" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt;" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="13a06-103">制限の種類。</span><span class="sxs-lookup"><span data-stu-id="13a06-103">The type of restrictions.</span></span> <span data-ttu-id="13a06-104">使用可能な値が含まれます: 'Location'、'ゾーン'</span><span class="sxs-lookup"><span data-stu-id="13a06-104">Possible values include: 'Location', 'Zone'</span></span></param>
        <param name="values"><span data-ttu-id="13a06-105">制限の値。</span><span class="sxs-lookup"><span data-stu-id="13a06-105">The value of restrictions.</span></span> <span data-ttu-id="13a06-106">場合は、制限の種類は、場所に設定されます。</span><span class="sxs-lookup"><span data-stu-id="13a06-106">If the restriction type is set to location.</span></span> <span data-ttu-id="13a06-107">SKU が制限されている別の場所になります。</span><span class="sxs-lookup"><span data-stu-id="13a06-107">This would be different locations where the SKU is restricted.</span></span></param>
        <param name="restrictionInfo"><span data-ttu-id="13a06-108">SKU が使用できないが、制限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="13a06-108">The information about the restriction where the SKU cannot be used.</span></span></param>
        <param name="reasonCode"><span data-ttu-id="13a06-109">制限の理由です。</span><span class="sxs-lookup"><span data-stu-id="13a06-109">The reason for restriction.</span></span> <span data-ttu-id="13a06-110">使用可能な値が含まれます: 'QuotaId'、'NotAvailableForSubscription'</span><span class="sxs-lookup"><span data-stu-id="13a06-110">Possible values include: 'QuotaId', 'NotAvailableForSubscription'</span></span></param>
        <summary>
            <span data-ttu-id="13a06-111">ResourceSkuRestrictions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13a06-111">Initializes a new instance of the ResourceSkuRestrictions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt; ReasonCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt; ReasonCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.ReasonCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReasonCode As Nullable(Of ResourceSkuRestrictionsReasonCode)" />
      <MemberSignature Language="F#" Value="member this.ReasonCode : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.ReasonCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsReasonCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13a06-112">制限の理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="13a06-112">Gets the reason for restriction.</span></span> <span data-ttu-id="13a06-113">使用可能な値が含まれます: 'QuotaId'、'NotAvailableForSubscription'</span><span class="sxs-lookup"><span data-stu-id="13a06-113">Possible values include: 'QuotaId', 'NotAvailableForSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestrictionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo RestrictionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo RestrictionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.RestrictionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestrictionInfo As ResourceSkuRestrictionInfo" />
      <MemberSignature Language="F#" Value="member this.RestrictionInfo : Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.RestrictionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="restrictionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13a06-114">SKU を使用することはできませんの制限についての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="13a06-114">Gets the information about the restriction where the SKU cannot be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt; Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As Nullable(Of ResourceSkuRestrictionsType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictionsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13a06-115">制限の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="13a06-115">Gets the type of restrictions.</span></span> <span data-ttu-id="13a06-116">使用可能な値が含まれます: 'Location'、'ゾーン'</span><span class="sxs-lookup"><span data-stu-id="13a06-116">Possible values include: 'Location', 'Zone'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Models.ResourceSkuRestrictions.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13a06-117">制限の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="13a06-117">Gets the value of restrictions.</span></span> <span data-ttu-id="13a06-118">場合は、制限の種類は、場所に設定されます。</span><span class="sxs-lookup"><span data-stu-id="13a06-118">If the restriction type is set to location.</span></span> <span data-ttu-id="13a06-119">SKU が制限されている別の場所になります。</span><span class="sxs-lookup"><span data-stu-id="13a06-119">This would be different locations where the SKU is restricted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>