<Type Name="StorageAccountProperties" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties">
  <TypeSignature Language="C#" Value="public class StorageAccountProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountProperties" />
  <TypeSignature Language="F#" Value="type StorageAccountProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8eafe-101">コンテナー レジストリのストレージ アカウントのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8eafe-101">The properties of a storage account for a container registry.</span></span> <span data-ttu-id="8eafe-102">従来の SKU にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="8eafe-102">Only applicable to Classic SKU.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8eafe-103">StorageAccountProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8eafe-103">Initializes a new instance of the StorageAccountProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountProperties (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties : string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8eafe-104">ストレージ アカウントのリソース ID です。</span><span class="sxs-lookup"><span data-stu-id="8eafe-104">The resource ID of the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="8eafe-105">StorageAccountProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8eafe-105">Initializes a new instance of the StorageAccountProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8eafe-106">取得またはストレージ アカウントのリソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="8eafe-106">Gets or sets the resource ID of the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8eafe-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8eafe-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8eafe-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8eafe-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>