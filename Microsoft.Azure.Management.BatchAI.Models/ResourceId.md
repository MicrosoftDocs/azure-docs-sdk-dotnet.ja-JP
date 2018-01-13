<Type Name="ResourceId" FullName="Microsoft.Azure.Management.BatchAI.Models.ResourceId">
  <TypeSignature Language="C#" Value="public class ResourceId : Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceId extends System.Object implements class Microsoft.Rest.Azure.IResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceId&#xA;Implements IResource" />
  <TypeSignature Language="F#" Value="type ResourceId = class&#xA;    interface IResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a7a7e-101">リソース ID を表します。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-101">Represents a resource ID.</span></span> <span data-ttu-id="a7a7e-102">たとえば、サブネットにはサブネットのリソース URL です。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-102">For example, for a subnet, it is the resource URL for the subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ResourceId.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7a7e-103">ResourceId クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-103">Initializes a new instance of the ResourceId class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ResourceId.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ResourceId : string -&gt; Microsoft.Azure.Management.BatchAI.Models.ResourceId" Usage="new Microsoft.Azure.Management.BatchAI.Models.ResourceId id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a7a7e-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="a7a7e-104">The ID of the resource</span></span></param>
        <summary>
            <span data-ttu-id="a7a7e-105">ResourceId クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-105">Initializes a new instance of the ResourceId class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ResourceId.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ResourceId.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7a7e-106">取得または設定、リソースの ID</span><span class="sxs-lookup"><span data-stu-id="a7a7e-106">Gets or sets the ID of the resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ResourceId.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceId.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7a7e-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a7a7e-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7a7e-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>