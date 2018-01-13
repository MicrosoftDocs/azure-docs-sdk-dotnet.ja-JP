<Type Name="PremierAddOnOffer" FullName="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer">
  <TypeSignature Language="C#" Value="public class PremierAddOnOffer : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PremierAddOnOffer extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer" />
  <TypeSignature Language="VB.NET" Value="Public Class PremierAddOnOffer&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PremierAddOnOffer = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            プレミア アドオン プランです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PremierAddOnOffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PremierAddOnOffer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PremierAddOnOffer (string id = null, string name = null, string kind = null, string type = null, string sku = null, string product = null, string vendor = null, string premierAddOnOfferName = null, Nullable&lt;bool&gt; promoCodeRequired = null, Nullable&lt;int&gt; quota = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; webHostingPlanRestrictions = null, string privacyPolicyUrl = null, string legalTermsUrl = null, string marketplacePublisher = null, string marketplaceOffer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string sku, string product, string vendor, string premierAddOnOfferName, valuetype System.Nullable`1&lt;bool&gt; promoCodeRequired, valuetype System.Nullable`1&lt;int32&gt; quota, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; webHostingPlanRestrictions, string privacyPolicyUrl, string legalTermsUrl, string marketplacePublisher, string marketplaceOffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional sku As String = null, Optional product As String = null, Optional vendor As String = null, Optional premierAddOnOfferName As String = null, Optional promoCodeRequired As Nullable(Of Boolean) = null, Optional quota As Nullable(Of Integer) = null, Optional webHostingPlanRestrictions As Nullable(Of AppServicePlanRestrictions) = null, Optional privacyPolicyUrl As String = null, Optional legalTermsUrl As String = null, Optional marketplacePublisher As String = null, Optional marketplaceOffer As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer : string * string * string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer" Usage="new Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer (id, name, kind, type, sku, product, vendor, premierAddOnOfferName, promoCodeRequired, quota, webHostingPlanRestrictions, privacyPolicyUrl, legalTermsUrl, marketplacePublisher, marketplaceOffer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="vendor" Type="System.String" />
        <Parameter Name="premierAddOnOfferName" Type="System.String" />
        <Parameter Name="promoCodeRequired" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="quota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="webHostingPlanRestrictions" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt;" />
        <Parameter Name="privacyPolicyUrl" Type="System.String" />
        <Parameter Name="legalTermsUrl" Type="System.String" />
        <Parameter Name="marketplacePublisher" Type="System.String" />
        <Parameter Name="marketplaceOffer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="sku">SKU。</param>
        <param name="product">製品です。</param>
        <param name="vendor">仕入先。</param>
        <param name="premierAddOnOfferName">名前。</param>
        <param name="promoCodeRequired">&lt;コード&gt;true&lt;/code&gt;プロモーション コードが必要なそれ以外の場合は&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="quota">クォータ。</param>
        <param name="webHostingPlanRestrictions">App Service プランにこのプランが制限されます。 使用可能な値が含まれます 'None'、'Free'、'Shared'、'Basic'、'Standard'、'Premium'。</param>
        <param name="privacyPolicyUrl">プライバシー ポリシー URL です。</param>
        <param name="legalTermsUrl">法律条項の URL です。</param>
        <param name="marketplacePublisher">Marketplace パブリッシャーです。</param>
        <param name="marketplaceOffer">Marketplace の提供。</param>
        <summary>
            PremierAddOnOffer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegalTermsUrl">
      <MemberSignature Language="C#" Value="public string LegalTermsUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LegalTermsUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.LegalTermsUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property LegalTermsUrl As String" />
      <MemberSignature Language="F#" Value="member this.LegalTermsUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.LegalTermsUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.legalTermsUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または法律条項の URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplaceOffer">
      <MemberSignature Language="C#" Value="public string MarketplaceOffer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MarketplaceOffer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.MarketplaceOffer" />
      <MemberSignature Language="VB.NET" Value="Public Property MarketplaceOffer As String" />
      <MemberSignature Language="F#" Value="member this.MarketplaceOffer : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.MarketplaceOffer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.marketplaceOffer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または marketplace の提供を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplacePublisher">
      <MemberSignature Language="C#" Value="public string MarketplacePublisher { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MarketplacePublisher" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.MarketplacePublisher" />
      <MemberSignature Language="VB.NET" Value="Public Property MarketplacePublisher As String" />
      <MemberSignature Language="F#" Value="member this.MarketplacePublisher : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.MarketplacePublisher" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.marketplacePublisher")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または marketplace 発行者を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremierAddOnOfferName">
      <MemberSignature Language="C#" Value="public string PremierAddOnOfferName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PremierAddOnOfferName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PremierAddOnOfferName" />
      <MemberSignature Language="VB.NET" Value="Public Property PremierAddOnOfferName As String" />
      <MemberSignature Language="F#" Value="member this.PremierAddOnOfferName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PremierAddOnOfferName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivacyPolicyUrl">
      <MemberSignature Language="C#" Value="public string PrivacyPolicyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivacyPolicyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PrivacyPolicyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivacyPolicyUrl As String" />
      <MemberSignature Language="F#" Value="member this.PrivacyPolicyUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PrivacyPolicyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privacyPolicyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプライバシー ポリシー URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Product" />
      <MemberSignature Language="VB.NET" Value="Public Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または製品を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromoCodeRequired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PromoCodeRequired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PromoCodeRequired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PromoCodeRequired" />
      <MemberSignature Language="VB.NET" Value="Public Property PromoCodeRequired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PromoCodeRequired : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.PromoCodeRequired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.promoCodeRequired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; プロモーション コードが必要な、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Quota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Quota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Quota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Quota" />
      <MemberSignature Language="VB.NET" Value="Public Property Quota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Quota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Quota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.quota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクォータを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vendor">
      <MemberSignature Language="C#" Value="public string Vendor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Vendor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Vendor" />
      <MemberSignature Language="VB.NET" Value="Public Property Vendor As String" />
      <MemberSignature Language="F#" Value="member this.Vendor : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.Vendor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vendor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仕入先を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebHostingPlanRestrictions">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; WebHostingPlanRestrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; WebHostingPlanRestrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.WebHostingPlanRestrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property WebHostingPlanRestrictions As Nullable(Of AppServicePlanRestrictions)" />
      <MemberSignature Language="F#" Value="member this.WebHostingPlanRestrictions : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer.WebHostingPlanRestrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webHostingPlanRestrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlanRestrictions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または app Service プランがこのプランはだけに制限を設定します。
            使用可能な値が含まれます 'None'、'Free'、'Shared'、'Basic'、'Standard'、'Premium'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>