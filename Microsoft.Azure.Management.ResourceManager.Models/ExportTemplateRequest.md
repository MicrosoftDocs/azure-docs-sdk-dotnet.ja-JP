<Type Name="ExportTemplateRequest" FullName="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest">
  <TypeSignature Language="C#" Value="public class ExportTemplateRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportTemplateRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportTemplateRequest" />
  <TypeSignature Language="F#" Value="type ExportTemplateRequest = class" />
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
            <span data-ttu-id="ba1de-101">リソース グループ テンプレート要求パラメーターをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="ba1de-101">Export resource group template request parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportTemplateRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba1de-102">ExportTemplateRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba1de-102">Initializes a new instance of the ExportTemplateRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportTemplateRequest (System.Collections.Generic.IList&lt;string&gt; resources = null, string options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; resources, string options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resources As IList(Of String) = null, Optional options As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest (resources, options)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="options" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resources"><span data-ttu-id="ba1de-103">リソースの Id。</span><span class="sxs-lookup"><span data-stu-id="ba1de-103">The IDs of the resources.</span></span> <span data-ttu-id="ba1de-104">唯一サポートされている文字列が現在は ' \*' (すべてのリソース)。</span><span class="sxs-lookup"><span data-stu-id="ba1de-104">The only supported string currently is '\*' (all resources).</span></span> <span data-ttu-id="ba1de-105">今後の更新は、特定のリソースのエクスポートをサポートします。</span><span class="sxs-lookup"><span data-stu-id="ba1de-105">Future updates will support exporting specific resources.</span></span></param>
        <param name="options"><span data-ttu-id="ba1de-106">テンプレートのエクスポート オプション。</span><span class="sxs-lookup"><span data-stu-id="ba1de-106">The export template options.</span></span> <span data-ttu-id="ba1de-107">サポートされている値は、'IncludeParameterDefaultValue'、'IncludeComments' または ' IncludeParameterDefaultValue、IncludeComments</span><span class="sxs-lookup"><span data-stu-id="ba1de-107">Supported values include 'IncludeParameterDefaultValue', 'IncludeComments' or 'IncludeParameterDefaultValue, IncludeComments</span></span></param>
        <summary>
            <span data-ttu-id="ba1de-108">ExportTemplateRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba1de-108">Initializes a new instance of the ExportTemplateRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Options">
      <MemberSignature Language="C#" Value="public string Options { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Options" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.Options" />
      <MemberSignature Language="VB.NET" Value="Public Property Options As String" />
      <MemberSignature Language="F#" Value="member this.Options : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.Options" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="options")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba1de-109">取得またはエクスポート テンプレート オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ba1de-109">Gets or sets the export template options.</span></span> <span data-ttu-id="ba1de-110">サポートされている値は、'IncludeParameterDefaultValue'、'IncludeComments' または ' IncludeParameterDefaultValue、IncludeComments</span><span class="sxs-lookup"><span data-stu-id="ba1de-110">Supported values include 'IncludeParameterDefaultValue', 'IncludeComments' or 'IncludeParameterDefaultValue, IncludeComments</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba1de-111">取得またはリソースの Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="ba1de-111">Gets or sets the IDs of the resources.</span></span> <span data-ttu-id="ba1de-112">唯一サポートされている文字列が現在は ' \*' (すべてのリソース)。</span><span class="sxs-lookup"><span data-stu-id="ba1de-112">The only supported string currently is '\*' (all resources).</span></span> <span data-ttu-id="ba1de-113">今後の更新は、特定のリソースのエクスポートをサポートします。</span><span class="sxs-lookup"><span data-stu-id="ba1de-113">Future updates will support exporting specific resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>