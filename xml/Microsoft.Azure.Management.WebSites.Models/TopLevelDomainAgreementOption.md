<Type Name="TopLevelDomainAgreementOption" FullName="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption">
  <TypeSignature Language="C#" Value="public class TopLevelDomainAgreementOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopLevelDomainAgreementOption extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" />
  <TypeSignature Language="VB.NET" Value="Public Class TopLevelDomainAgreementOption" />
  <TypeSignature Language="F#" Value="type TopLevelDomainAgreementOption = class" />
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
            <span data-ttu-id="9fe67-101">最上位ドメイン法的契約の一覧を取得するためのオプションです。</span><span class="sxs-lookup"><span data-stu-id="9fe67-101">Options for retrieving the list of top level domain legal agreements.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomainAgreementOption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9fe67-102">TopLevelDomainAgreementOption クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9fe67-102">Initializes a new instance of the TopLevelDomainAgreementOption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopLevelDomainAgreementOption (Nullable&lt;bool&gt; includePrivacy = null, Nullable&lt;bool&gt; forTransfer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; includePrivacy, valuetype System.Nullable`1&lt;bool&gt; forTransfer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.#ctor(System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional includePrivacy As Nullable(Of Boolean) = null, Optional forTransfer As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption : Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" Usage="new Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption (includePrivacy, forTransfer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="includePrivacy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forTransfer" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="includePrivacy"><span data-ttu-id="9fe67-103">場合&lt;コード&gt;true&lt;/code&gt;、同様ですそれ以外の場合は、アグリーメントの一覧にドメインのプライバシー保護のためのアグリーメントが含まれます&lt;コード&gt;false&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="9fe67-103">If &lt;code&gt;true&lt;/code&gt;, then the list of agreements will include agreements for domain privacy as well; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="forTransfer"><span data-ttu-id="9fe67-104">場合&lt;コード&gt;true&lt;/code&gt;、同様ですそれ以外の場合は、アグリーメントの一覧にドメイン転送の契約が含まれます&lt;コード&gt;false&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="9fe67-104">If &lt;code&gt;true&lt;/code&gt;, then the list of agreements will include agreements for domain transfer as well; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <summary>
            <span data-ttu-id="9fe67-105">TopLevelDomainAgreementOption クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9fe67-105">Initializes a new instance of the TopLevelDomainAgreementOption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForTransfer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForTransfer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForTransfer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.ForTransfer" />
      <MemberSignature Language="VB.NET" Value="Public Property ForTransfer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForTransfer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.ForTransfer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forTransfer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe67-106">取得または設定場合&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt 以外の場合は、同様です。 それ以外の場合は、アグリーメントの一覧にドメイン転送の契約が含まれます&amp;lt; コード&amp;gt; false。&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="9fe67-106">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, then the list of agreements will include agreements for domain transfer as well; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludePrivacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludePrivacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludePrivacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.IncludePrivacy" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludePrivacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludePrivacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption.IncludePrivacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includePrivacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9fe67-107">取得または設定場合&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt 以外の場合は、同様です。 それ以外の場合は、アグリーメントの一覧にドメインのプライバシー保護のためのアグリーメントが含まれます&amp;lt; コード&amp;gt; false。&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="9fe67-107">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, then the list of agreements will include agreements for domain privacy as well; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>