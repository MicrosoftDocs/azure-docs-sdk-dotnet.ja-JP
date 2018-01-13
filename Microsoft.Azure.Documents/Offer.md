<Type Name="Offer" FullName="Microsoft.Azure.Documents.Offer">
  <TypeSignature Language="C#" Value="public class Offer : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Offer extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Offer" />
  <TypeSignature Language="VB.NET" Value="Public Class Offer&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Offer = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0b265-101">Azure Cosmos DB サービスのリソース (コレクション) 用のプランを表します。</span><span class="sxs-lookup"><span data-stu-id="0b265-101">Represents the offer for a resource (collection) in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0b265-102">現時点では、オファーは、コレクション リソースにのみバインドされます。</span><span class="sxs-lookup"><span data-stu-id="0b265-102">Currently, offers are only bound to the collection resource.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Offer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Offer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0b265-103">Azure Cosmos DB サービスのリソースのオファーを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0b265-103">Initializes a Resource offer for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Offer (Microsoft.Azure.Documents.Offer offer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Offer offer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Offer.#ctor(Microsoft.Azure.Documents.Offer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Offer : Microsoft.Azure.Documents.Offer -&gt; Microsoft.Azure.Documents.Offer" Usage="new Microsoft.Azure.Documents.Offer offer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offer" Type="Microsoft.Azure.Documents.Offer" />
      </Parameters>
      <Docs>
        <param name="offer">To be added.</param>
        <summary>
            <span data-ttu-id="0b265-104">Azure Cosmos DB サービスの別のオファー オブジェクトから、リソースの購入プランを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0b265-104">Initializes a Resource offer from another offer object for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OfferType">
      <MemberSignature Language="C#" Value="public string OfferType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OfferType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Offer.OfferType" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferType As String" />
      <MemberSignature Language="F#" Value="member this.OfferType : string with get, set" Usage="Microsoft.Azure.Documents.Offer.OfferType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="offerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b265-105">取得または Azure Cosmos DB サービスのリソース提供 OfferType を設定します。</span><span class="sxs-lookup"><span data-stu-id="0b265-105">Gets or sets the OfferType for the resource offer in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OfferVersion">
      <MemberSignature Language="C#" Value="public string OfferVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OfferVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Offer.OfferVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OfferVersion As String" />
      <MemberSignature Language="F#" Value="member this.OfferVersion : string" Usage="Microsoft.Azure.Documents.Offer.OfferVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="offerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b265-106">取得または Azure Cosmos DB サービスでこのオファー リソースのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="0b265-106">Gets or sets the version of this offer resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceLink">
      <MemberSignature Language="C#" Value="public string ResourceLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Offer.ResourceLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceLink As String" />
      <MemberSignature Language="F#" Value="member this.ResourceLink : string" Usage="Microsoft.Azure.Documents.Offer.ResourceLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b265-107">取得または Azure Cosmos DB サービスのリソースの提供に適用されるリソースの自己リンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="0b265-107">Gets or sets the self-link of a resource to which the resource offer applies to in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>