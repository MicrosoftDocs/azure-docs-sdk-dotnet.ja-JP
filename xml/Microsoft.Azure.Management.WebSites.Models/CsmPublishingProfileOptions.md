<Type Name="CsmPublishingProfileOptions" FullName="Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions">
  <TypeSignature Language="C#" Value="public class CsmPublishingProfileOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsmPublishingProfileOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class CsmPublishingProfileOptions" />
  <TypeSignature Language="F#" Value="type CsmPublishingProfileOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ae3fe-101">要求されたプロファイルのオプションを公開します。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-101">Publishing options for requested profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmPublishingProfileOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ae3fe-102">CsmPublishingProfileOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-102">Initializes a new instance of the CsmPublishingProfileOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmPublishingProfileOptions (string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions : string -&gt; Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions" Usage="new Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions format" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="format"><span data-ttu-id="ae3fe-103">形式の名前。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-103">Name of the format.</span></span> <span data-ttu-id="ae3fe-104">有効な値: FileZilla3 WebDeploy - 既定の Ftp です。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-104">Valid values are: FileZilla3 WebDeploy -- default Ftp.</span></span> <span data-ttu-id="ae3fe-105">使用可能な値が含まれます: 'FileZilla3'、'WebDeploy'、'Ftp'</span><span class="sxs-lookup"><span data-stu-id="ae3fe-105">Possible values include: 'FileZilla3', 'WebDeploy', 'Ftp'</span></span></param>
        <summary>
            <span data-ttu-id="ae3fe-106">CsmPublishingProfileOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-106">Initializes a new instance of the CsmPublishingProfileOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmPublishingProfileOptions.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae3fe-107">取得または形式の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-107">Gets or sets name of the format.</span></span> <span data-ttu-id="ae3fe-108">有効な値: FileZilla3 WebDeploy - 既定の Ftp です。</span><span class="sxs-lookup"><span data-stu-id="ae3fe-108">Valid values are: FileZilla3 WebDeploy -- default Ftp.</span></span> <span data-ttu-id="ae3fe-109">使用可能な値が含まれます: 'FileZilla3'、'WebDeploy'、'Ftp'</span><span class="sxs-lookup"><span data-stu-id="ae3fe-109">Possible values include: 'FileZilla3', 'WebDeploy', 'Ftp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>