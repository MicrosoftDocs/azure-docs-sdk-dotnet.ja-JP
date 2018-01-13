<Type Name="StorageMigrationResponse" FullName="Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse">
  <TypeSignature Language="C#" Value="public class StorageMigrationResponse : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageMigrationResponse extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageMigrationResponse&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type StorageMigrationResponse = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9b316-101">アプリのコンテンツ要求の移行の応答。</span><span class="sxs-lookup"><span data-stu-id="9b316-101">Response for a migration of app content request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9b316-102">StorageMigrationResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b316-102">Initializes a new instance of the StorageMigrationResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationResponse (string id = null, string name = null, string kind = null, string type = null, string operationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional operationId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse : string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse" Usage="new Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse (id, name, kind, type, operationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="9b316-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="9b316-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="9b316-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="9b316-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="9b316-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="9b316-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="9b316-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="9b316-106">Resource type.</span></span></param>
        <param name="operationId"><span data-ttu-id="9b316-107">サーバーが移行プロセスを開始するときに、その特定の移行操作を識別する操作 ID を返します。</span><span class="sxs-lookup"><span data-stu-id="9b316-107">When server starts the migration process, it will return an operation ID identifying that particular migration operation.</span></span></param>
        <summary>
            <span data-ttu-id="9b316-108">StorageMigrationResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b316-108">Initializes a new instance of the StorageMigrationResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.WebSites.Models.StorageMigrationResponse.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b316-109">サーバー移行プロセスの開始時に取得して、その特定の移行操作を識別する操作 ID を返します。</span><span class="sxs-lookup"><span data-stu-id="9b316-109">Gets when server starts the migration process, it will return an operation ID identifying that particular migration operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>