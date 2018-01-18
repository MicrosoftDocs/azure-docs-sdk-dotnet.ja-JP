<Type Name="ResourceLinkProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties">
  <TypeSignature Language="C#" Value="public class ResourceLinkProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceLinkProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceLinkProperties" />
  <TypeSignature Language="F#" Value="type ResourceLinkProperties = class" />
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
            <span data-ttu-id="b9a91-101">リソース リンクのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="b9a91-101">The resource link properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b9a91-102">ResourceLinkProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-102">Initializes a new instance of the ResourceLinkProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkProperties (string targetId, string sourceId = null, string notes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetId, string sourceId, string notes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetId As String, Optional sourceId As String = null, Optional notes As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties : string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties (targetId, sourceId, notes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetId" Type="System.String" />
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="notes" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetId"><span data-ttu-id="b9a91-103">リンクのターゲット リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="b9a91-103">The fully qualified ID of the target resource in the link.</span></span></param>
        <param name="sourceId"><span data-ttu-id="b9a91-104">リンクのソースのリソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="b9a91-104">The fully qualified ID of the source resource in the link.</span></span> </param>
        <param name="notes"><span data-ttu-id="b9a91-105">リソース リンクに関する注意事項です。</span><span class="sxs-lookup"><span data-stu-id="b9a91-105">Notes about the resource link.</span></span></param>
        <summary>
            <span data-ttu-id="b9a91-106">ResourceLinkProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-106">Initializes a new instance of the ResourceLinkProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notes">
      <MemberSignature Language="C#" Value="public string Notes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Notes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Notes" />
      <MemberSignature Language="VB.NET" Value="Public Property Notes As String" />
      <MemberSignature Language="F#" Value="member this.Notes : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Notes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="notes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9a91-107">取得またはリソースのリンクに関する注意事項を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-107">Gets or sets notes about the resource link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.SourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9a91-108">リンクのソースのリソースの完全修飾 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-108">Gets the fully qualified ID of the source resource in the link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetId">
      <MemberSignature Language="C#" Value="public string TargetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.TargetId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetId As String" />
      <MemberSignature Language="F#" Value="member this.TargetId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.TargetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9a91-109">取得またはリンクのターゲット リソースの完全修飾 ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-109">Gets or sets the fully qualified ID of the target resource in the link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceLinkProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b9a91-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b9a91-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9a91-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9a91-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>