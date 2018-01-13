<Type Name="DomainAvailablilityCheckResult" FullName="Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult">
  <TypeSignature Language="C#" Value="public class DomainAvailablilityCheckResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainAvailablilityCheckResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainAvailablilityCheckResult" />
  <TypeSignature Language="F#" Value="type DomainAvailablilityCheckResult = class" />
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
            <span data-ttu-id="adadb-101">ドメインの可用性のチェックの結果。</span><span class="sxs-lookup"><span data-stu-id="adadb-101">Domain availablility check result.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainAvailablilityCheckResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adadb-102">DomainAvailablilityCheckResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="adadb-102">Initializes a new instance of the DomainAvailablilityCheckResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainAvailablilityCheckResult (string name = null, Nullable&lt;bool&gt; available = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt; domainType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; available, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainType&gt; domainType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.WebSites.Models.DomainType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional available As Nullable(Of Boolean) = null, Optional domainType As Nullable(Of DomainType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult : string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult" Usage="new Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult (name, available, domainType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="available" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="domainType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="adadb-103">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="adadb-103">Name of the domain.</span></span></param>
        <param name="available"><span data-ttu-id="adadb-104">&lt;コード&gt;true&lt;/code&gt; CreateDomain API を使用して購入した、それ以外のドメインができる場合&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="adadb-104">&lt;code&gt;true&lt;/code&gt; if domain can be purchased using CreateDomain API; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="domainType"><span data-ttu-id="adadb-105">有効な値は正規ドメイン: Azure がドメインの登録、SoftDeleted の通常の価格を充電: このドメインを購入、単に元に戻るし、この操作では何もコストはありません。</span><span class="sxs-lookup"><span data-stu-id="adadb-105">Valid values are Regular domain: Azure will charge the full price of domain registration, SoftDeleted: Purchasing this domain will simply restore it and this operation will not cost anything.</span></span> <span data-ttu-id="adadb-106">使用可能な値が含まれます: '標準'、'SoftDeleted'</span><span class="sxs-lookup"><span data-stu-id="adadb-106">Possible values include: 'Regular', 'SoftDeleted'</span></span></param>
        <summary>
            <span data-ttu-id="adadb-107">DomainAvailablilityCheckResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="adadb-107">Initializes a new instance of the DomainAvailablilityCheckResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Available { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.Available" />
      <MemberSignature Language="VB.NET" Value="Public Property Available As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Available : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adadb-108">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; CreateDomain API を使用して購入した、それ以外のドメインができる場合&amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="adadb-108">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if domain can be purchased using CreateDomain API; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt; DomainType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.DomainType&gt; DomainType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.DomainType" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainType As Nullable(Of DomainType)" />
      <MemberSignature Language="F#" Value="member this.DomainType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.DomainType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="domainType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.DomainType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adadb-109">取得または設定が有効な値は、正規ドメイン: Azure がドメインの登録、SoftDeleted の通常の価格を充電: このドメインを購入、単に元に戻るし、この操作では何もコストはありません。</span><span class="sxs-lookup"><span data-stu-id="adadb-109">Gets or sets valid values are Regular domain: Azure will charge the full price of domain registration, SoftDeleted: Purchasing this domain will simply restore it and this operation will not cost anything.</span></span> <span data-ttu-id="adadb-110">使用可能な値が含まれます: '標準'、'SoftDeleted'</span><span class="sxs-lookup"><span data-stu-id="adadb-110">Possible values include: 'Regular', 'SoftDeleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult.Name" />
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
            <span data-ttu-id="adadb-111">取得またはドメインの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="adadb-111">Gets or sets name of the domain.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>