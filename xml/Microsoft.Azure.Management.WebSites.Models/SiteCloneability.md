<Type Name="SiteCloneability" FullName="Microsoft.Azure.Management.WebSites.Models.SiteCloneability">
  <TypeSignature Language="C#" Value="public class SiteCloneability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteCloneability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteCloneability" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteCloneability" />
  <TypeSignature Language="F#" Value="type SiteCloneability = class" />
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
            <span data-ttu-id="bb5eb-101">アプリが複製可能かどうかを表します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-101">Represents whether or not an app is cloneable.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteCloneability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bb5eb-102">SiteCloneability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-102">Initializes a new instance of the SiteCloneability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteCloneability (Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; result = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; blockingFeatures = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; unsupportedFeatures = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; blockingCharacteristics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; result, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; blockingFeatures, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; unsupportedFeatures, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; blockingCharacteristics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.#ctor(System.Nullable{Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional result As Nullable(Of CloneAbilityResult) = null, Optional blockingFeatures As IList(Of SiteCloneabilityCriterion) = null, Optional unsupportedFeatures As IList(Of SiteCloneabilityCriterion) = null, Optional blockingCharacteristics As IList(Of SiteCloneabilityCriterion) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteCloneability : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteCloneability" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteCloneability (result, blockingFeatures, unsupportedFeatures, blockingCharacteristics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt;" />
        <Parameter Name="blockingFeatures" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;" />
        <Parameter Name="unsupportedFeatures" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;" />
        <Parameter Name="blockingCharacteristics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="bb5eb-103">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-103">Name of app.</span></span> <span data-ttu-id="bb5eb-104">使用可能な値が含まれます: '複製可能な'、'PartiallyCloneable'、'NotCloneable'</span><span class="sxs-lookup"><span data-stu-id="bb5eb-104">Possible values include: 'Cloneable', 'PartiallyCloneable', 'NotCloneable'</span></span></param>
        <param name="blockingFeatures"><span data-ttu-id="bb5eb-105">複製を禁止するアプリで有効になっている機能の一覧です。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-105">List of features enabled on app that prevent cloning.</span></span></param>
        <param name="unsupportedFeatures"><span data-ttu-id="bb5eb-106">ある非ブロッキングしますですが、複製できません。 アプリで有効になっている機能の一覧です。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-106">List of features enabled on app that are non-blocking but cannot be cloned.</span></span> <span data-ttu-id="bb5eb-107">クローンとして作成されたアプリ上に、この一覧にある機能に設定できませんが、アプリを複製まだことができます。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-107">The app can still be cloned but the features in this list will not be set up on cloned app.</span></span></param>
        <param name="blockingCharacteristics"><span data-ttu-id="bb5eb-108">アプリケーションの特性をブロックの一覧です。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-108">List of blocking application characteristics.</span></span></param>
        <summary>
            <span data-ttu-id="bb5eb-109">SiteCloneability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-109">Initializes a new instance of the SiteCloneability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockingCharacteristics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; BlockingCharacteristics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; BlockingCharacteristics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.BlockingCharacteristics" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockingCharacteristics As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.BlockingCharacteristics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteCloneability.BlockingCharacteristics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blockingCharacteristics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb5eb-110">取得またはアプリケーションの特性をブロックの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-110">Gets or sets list of blocking application characteristics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockingFeatures">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; BlockingFeatures { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; BlockingFeatures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.BlockingFeatures" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockingFeatures As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.BlockingFeatures : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteCloneability.BlockingFeatures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blockingFeatures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb5eb-111">取得または複製を禁止するアプリで有効になっている機能の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-111">Gets or sets list of features enabled on app that prevent cloning.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of CloneAbilityResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteCloneability.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CloneAbilityResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb5eb-112">取得またはアプリの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-112">Gets or sets name of app.</span></span> <span data-ttu-id="bb5eb-113">使用可能な値が含まれます: '複製可能な'、'PartiallyCloneable'、'NotCloneable'</span><span class="sxs-lookup"><span data-stu-id="bb5eb-113">Possible values include: 'Cloneable', 'PartiallyCloneable', 'NotCloneable'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnsupportedFeatures">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; UnsupportedFeatures { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; UnsupportedFeatures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteCloneability.UnsupportedFeatures" />
      <MemberSignature Language="VB.NET" Value="Public Property UnsupportedFeatures As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.UnsupportedFeatures : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteCloneability.UnsupportedFeatures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unsupportedFeatures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb5eb-114">取得またはアプリで有効にされている非ブロッキングしますですが、複製できません。 機能の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-114">Gets or sets list of features enabled on app that are non-blocking but cannot be cloned.</span></span> <span data-ttu-id="bb5eb-115">クローンとして作成されたアプリ上に、この一覧にある機能に設定できませんが、アプリを複製まだことができます。</span><span class="sxs-lookup"><span data-stu-id="bb5eb-115">The app can still be cloned but the features in this list will not be set up on cloned app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>