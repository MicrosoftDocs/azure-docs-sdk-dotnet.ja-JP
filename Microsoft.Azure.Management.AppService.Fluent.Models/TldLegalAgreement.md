<Type Name="TldLegalAgreement" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement">
  <TypeSignature Language="C#" Value="public class TldLegalAgreement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TldLegalAgreement extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement" />
  <TypeSignature Language="VB.NET" Value="Public Class TldLegalAgreement" />
  <TypeSignature Language="F#" Value="type TldLegalAgreement = class" />
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
            <span data-ttu-id="484ee-101">最上位ドメインの法的契約。</span><span class="sxs-lookup"><span data-stu-id="484ee-101">Legal agreement for a top level domain.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TldLegalAgreement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="484ee-102">TldLegalAgreement クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="484ee-102">Initializes a new instance of the TldLegalAgreement class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TldLegalAgreement (string agreementKey, string title, string content, string url = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string agreementKey, string title, string content, string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (agreementKey As String, title As String, content As String, Optional url As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement : string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement (agreementKey, title, content, url)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="agreementKey" Type="System.String" />
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="agreementKey"><span data-ttu-id="484ee-103">アグリーメントの一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="484ee-103">Unique identifier for the agreement.</span></span></param>
        <param name="title"><span data-ttu-id="484ee-104">アグリーメントのタイトルです。</span><span class="sxs-lookup"><span data-stu-id="484ee-104">Agreement title.</span></span></param>
        <param name="content"><span data-ttu-id="484ee-105">契約の詳細。</span><span class="sxs-lookup"><span data-stu-id="484ee-105">Agreement details.</span></span></param>
        <param name="url"><span data-ttu-id="484ee-106">契約の詳細のコピーがホストされている URL です。</span><span class="sxs-lookup"><span data-stu-id="484ee-106">URL where a copy of the agreement details is hosted.</span></span></param>
        <summary>
            <span data-ttu-id="484ee-107">TldLegalAgreement クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="484ee-107">Initializes a new instance of the TldLegalAgreement class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgreementKey">
      <MemberSignature Language="C#" Value="public string AgreementKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AgreementKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.AgreementKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AgreementKey As String" />
      <MemberSignature Language="F#" Value="member this.AgreementKey : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.AgreementKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="agreementKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="484ee-108">取得またはアグリーメントの一意の識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="484ee-108">Gets or sets unique identifier for the agreement.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public string Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As String" />
      <MemberSignature Language="F#" Value="member this.Content : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="484ee-109">取得または契約の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="484ee-109">Gets or sets agreement details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="484ee-110">取得またはアグリーメントのタイトルを設定します。</span><span class="sxs-lookup"><span data-stu-id="484ee-110">Gets or sets agreement title.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="484ee-111">取得または契約の詳細のコピーがホストされている URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="484ee-111">Gets or sets URL where a copy of the agreement details is hosted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tldLegalAgreement.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="484ee-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="484ee-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="484ee-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="484ee-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>