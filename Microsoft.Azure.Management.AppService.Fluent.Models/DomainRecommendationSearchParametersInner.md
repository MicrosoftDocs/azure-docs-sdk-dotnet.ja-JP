<Type Name="DomainRecommendationSearchParametersInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner">
  <TypeSignature Language="C#" Value="public class DomainRecommendationSearchParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainRecommendationSearchParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainRecommendationSearchParametersInner" />
  <TypeSignature Language="F#" Value="type DomainRecommendationSearchParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e5626-101">ドメイン推奨設定の検索パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e5626-101">Domain recommendation search parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainRecommendationSearchParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e5626-102">DomainRecommendationSearchParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5626-102">Initializes a new instance of the DomainRecommendationSearchParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainRecommendationSearchParametersInner (string keywords = null, Nullable&lt;int&gt; maxDomainRecommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keywords, valuetype System.Nullable`1&lt;int32&gt; maxDomainRecommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keywords As String = null, Optional maxDomainRecommendations As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner (keywords, maxDomainRecommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keywords" Type="System.String" />
        <Parameter Name="maxDomainRecommendations" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="keywords"><span data-ttu-id="e5626-103">ドメインの推奨設定の作成に使用するキーワードです。</span><span class="sxs-lookup"><span data-stu-id="e5626-103">Keywords to be used for generating domain recommendations.</span></span></param>
        <param name="maxDomainRecommendations"><span data-ttu-id="e5626-104">推奨設定の最大数。</span><span class="sxs-lookup"><span data-stu-id="e5626-104">Maximum number of recommendations.</span></span></param>
        <summary>
            <span data-ttu-id="e5626-105">DomainRecommendationSearchParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5626-105">Initializes a new instance of the DomainRecommendationSearchParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keywords">
      <MemberSignature Language="C#" Value="public string Keywords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Keywords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.Keywords" />
      <MemberSignature Language="VB.NET" Value="Public Property Keywords As String" />
      <MemberSignature Language="F#" Value="member this.Keywords : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.Keywords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keywords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5626-106">取得またはドメインの推奨設定の作成に使用するキーワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5626-106">Gets or sets keywords to be used for generating domain recommendations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDomainRecommendations">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDomainRecommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDomainRecommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.MaxDomainRecommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDomainRecommendations As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDomainRecommendations : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner.MaxDomainRecommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDomainRecommendations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5626-107">取得または推奨の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="e5626-107">Gets or sets maximum number of recommendations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>