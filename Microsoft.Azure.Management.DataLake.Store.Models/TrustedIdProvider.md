<Type Name="TrustedIdProvider" FullName="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider">
  <TypeSignature Language="C#" Value="public class TrustedIdProvider : Microsoft.Azure.Management.DataLake.Store.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TrustedIdProvider extends Microsoft.Azure.Management.DataLake.Store.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class TrustedIdProvider&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type TrustedIdProvider = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9338a-101">データ ストアの信頼された Id プロバイダーの Lake 情報</span><span class="sxs-lookup"><span data-stu-id="9338a-101">Data Lake Store Trusted Identity Provider information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrustedIdProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9338a-102">TrustedIdProvider クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9338a-102">Initializes a new instance of the TrustedIdProvider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrustedIdProvider (string idProvider, string id = null, string name = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string idProvider, string id, string name, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (idProvider As String, Optional id As String = null, Optional name As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider : string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider (idProvider, id, name, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="idProvider" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="idProvider"><span data-ttu-id="9338a-103">この信頼された id プロバイダーの URL</span><span class="sxs-lookup"><span data-stu-id="9338a-103">The URL of this trusted identity provider</span></span></param>
        <param name="id"><span data-ttu-id="9338a-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="9338a-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="9338a-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="9338a-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="9338a-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="9338a-106">Resource type</span></span></param>
        <summary>
            <span data-ttu-id="9338a-107">TrustedIdProvider クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9338a-107">Initializes a new instance of the TrustedIdProvider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdProvider">
      <MemberSignature Language="C#" Value="public string IdProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider.IdProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property IdProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdProvider : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider.IdProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9338a-108">取得またはこの信頼された id プロバイダーの URL を設定</span><span class="sxs-lookup"><span data-stu-id="9338a-108">Gets or sets the URL of this trusted identity provider</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="trustedIdProvider.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9338a-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9338a-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9338a-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9338a-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>