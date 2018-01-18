<Type Name="DiagnosticSettingsCategoryResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource">
  <TypeSignature Language="C#" Value="public class DiagnosticSettingsCategoryResource : Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticSettingsCategoryResource extends Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticSettingsCategoryResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type DiagnosticSettingsCategoryResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="567f1-101">診断設定のカテゴリのリソース。</span><span class="sxs-lookup"><span data-stu-id="567f1-101">The diagnostic settings category resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsCategoryResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="567f1-102">DiagnosticSettingsCategoryResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="567f1-102">Initializes a new instance of the DiagnosticSettingsCategoryResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsCategoryResource (string id = null, string name = null, string type = null, Microsoft.Azure.Management.Monitor.Management.Models.CategoryType categoryType = Microsoft.Azure.Management.Monitor.Management.Models.CategoryType.Metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype Microsoft.Azure.Management.Monitor.Management.Models.CategoryType categoryType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.CategoryType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource : string * string * string * Microsoft.Azure.Management.Monitor.Management.Models.CategoryType -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource (id, name, type, categoryType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="categoryType" Type="Microsoft.Azure.Management.Monitor.Management.Models.CategoryType" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="567f1-103">Azure のリソース Id</span><span class="sxs-lookup"><span data-stu-id="567f1-103">Azure resource Id</span></span></param>
        <param name="name"><span data-ttu-id="567f1-104">Azure のリソース名</span><span class="sxs-lookup"><span data-stu-id="567f1-104">Azure resource name</span></span></param>
        <param name="type"><span data-ttu-id="567f1-105">Azure リソースの種類</span><span class="sxs-lookup"><span data-stu-id="567f1-105">Azure resource type</span></span></param>
        <param name="categoryType"><span data-ttu-id="567f1-106">診断設定のカテゴリの型。</span><span class="sxs-lookup"><span data-stu-id="567f1-106">The type of the diagnostic settings category.</span></span> <span data-ttu-id="567f1-107">使用可能な値が含まれます: 'メトリック'、'ログ'</span><span class="sxs-lookup"><span data-stu-id="567f1-107">Possible values include: 'Metrics', 'Logs'</span></span></param>
        <summary>
            <span data-ttu-id="567f1-108">DiagnosticSettingsCategoryResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="567f1-108">Initializes a new instance of the DiagnosticSettingsCategoryResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CategoryType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.CategoryType CategoryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.CategoryType CategoryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.CategoryType" />
      <MemberSignature Language="VB.NET" Value="Public Property CategoryType As CategoryType" />
      <MemberSignature Language="F#" Value="member this.CategoryType : Microsoft.Azure.Management.Monitor.Management.Models.CategoryType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.CategoryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.categoryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.CategoryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="567f1-109">取得または設定カテゴリの診断設定の種類。</span><span class="sxs-lookup"><span data-stu-id="567f1-109">Gets or sets the type of the diagnostic settings category.</span></span> <span data-ttu-id="567f1-110">使用可能な値が含まれます: 'メトリック'、'ログ'</span><span class="sxs-lookup"><span data-stu-id="567f1-110">Possible values include: 'Metrics', 'Logs'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>