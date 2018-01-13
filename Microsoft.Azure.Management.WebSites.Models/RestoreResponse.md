<Type Name="RestoreResponse" FullName="Microsoft.Azure.Management.WebSites.Models.RestoreResponse">
  <TypeSignature Language="C#" Value="public class RestoreResponse : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreResponse extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RestoreResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreResponse&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RestoreResponse = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="33777-101">アプリの復元要求の応答。</span><span class="sxs-lookup"><span data-stu-id="33777-101">Response for an app restore request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="33777-102">RestoreResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33777-102">Initializes a new instance of the RestoreResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreResponse (string id = null, string name = null, string kind = null, string type = null, string operationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreResponse.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional operationId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RestoreResponse : string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RestoreResponse" Usage="new Microsoft.Azure.Management.WebSites.Models.RestoreResponse (id, name, kind, type, operationId)" />
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
        <param name="id"><span data-ttu-id="33777-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="33777-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="33777-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="33777-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="33777-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="33777-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="33777-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="33777-106">Resource type.</span></span></param>
        <param name="operationId"><span data-ttu-id="33777-107">サーバーが、復元プロセスを開始するときに、その特定の復元操作を識別する操作 ID を返します。</span><span class="sxs-lookup"><span data-stu-id="33777-107">When server starts the restore process, it will return an operation ID identifying that particular restore operation.</span></span></param>
        <summary>
            <span data-ttu-id="33777-108">RestoreResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33777-108">Initializes a new instance of the RestoreResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreResponse.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreResponse.OperationId" />
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
            <span data-ttu-id="33777-109">サーバー復元プロセスの開始時に取得して、その特定の復元操作を識別する操作 ID を返します。</span><span class="sxs-lookup"><span data-stu-id="33777-109">Gets when server starts the restore process, it will return an operation ID identifying that particular restore operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>