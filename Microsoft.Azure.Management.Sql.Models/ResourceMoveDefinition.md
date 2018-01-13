<Type Name="ResourceMoveDefinition" FullName="Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition">
  <TypeSignature Language="C#" Value="public class ResourceMoveDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMoveDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMoveDefinition" />
  <TypeSignature Language="F#" Value="type ResourceMoveDefinition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2721b-101">リソースの移動 (rename) の実行に必要な情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2721b-101">Contains the information necessary to perform a resource move (rename).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMoveDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2721b-102">ResourceMoveDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2721b-102">Initializes a new instance of the ResourceMoveDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMoveDefinition (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition : string -&gt; Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition" Usage="new Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2721b-103">リソースの移動先の ID</span><span class="sxs-lookup"><span data-stu-id="2721b-103">The target ID for the resource</span></span></param>
        <summary>
            <span data-ttu-id="2721b-104">ResourceMoveDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2721b-104">Initializes a new instance of the ResourceMoveDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="2721b-105">取得または設定、リソースのターゲット ID</span><span class="sxs-lookup"><span data-stu-id="2721b-105">Gets or sets the target ID for the resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceMoveDefinition.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2721b-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2721b-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2721b-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2721b-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>