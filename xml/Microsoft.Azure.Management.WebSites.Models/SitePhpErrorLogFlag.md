<Type Name="SitePhpErrorLogFlag" FullName="Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag">
  <TypeSignature Language="C#" Value="public class SitePhpErrorLogFlag : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SitePhpErrorLogFlag extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag" />
  <TypeSignature Language="VB.NET" Value="Public Class SitePhpErrorLogFlag&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SitePhpErrorLogFlag = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="46217-101">PHP のエラー ログのフラグを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46217-101">Used for getting PHP error logging flag.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SitePhpErrorLogFlag ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="46217-102">SitePhpErrorLogFlag クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46217-102">Initializes a new instance of the SitePhpErrorLogFlag class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SitePhpErrorLogFlag (string id = null, string name = null, string kind = null, string type = null, string localLogErrors = null, string masterLogErrors = null, string localLogErrorsMaxLength = null, string masterLogErrorsMaxLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string localLogErrors, string masterLogErrors, string localLogErrorsMaxLength, string masterLogErrorsMaxLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional localLogErrors As String = null, Optional masterLogErrors As String = null, Optional localLogErrorsMaxLength As String = null, Optional masterLogErrorsMaxLength As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag" Usage="new Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag (id, name, kind, type, localLogErrors, masterLogErrors, localLogErrorsMaxLength, masterLogErrorsMaxLength)" />
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
        <Parameter Name="localLogErrors" Type="System.String" />
        <Parameter Name="masterLogErrors" Type="System.String" />
        <Parameter Name="localLogErrorsMaxLength" Type="System.String" />
        <Parameter Name="masterLogErrorsMaxLength" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="46217-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="46217-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="46217-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="46217-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="46217-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="46217-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="46217-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="46217-106">Resource type.</span></span></param>
        <param name="localLogErrors"><span data-ttu-id="46217-107">ローカル log_errors 設定です。</span><span class="sxs-lookup"><span data-stu-id="46217-107">Local log_errors setting.</span></span></param>
        <param name="masterLogErrors"><span data-ttu-id="46217-108">マスター log_errors を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-108">Master log_errors setting.</span></span></param>
        <param name="localLogErrorsMaxLength"><span data-ttu-id="46217-109">ローカル log_errors_max_len 設定です。</span><span class="sxs-lookup"><span data-stu-id="46217-109">Local log_errors_max_len setting.</span></span></param>
        <param name="masterLogErrorsMaxLength"><span data-ttu-id="46217-110">マスター log_errors_max_len を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-110">Master log_errors_max_len setting.</span></span></param>
        <summary>
            <span data-ttu-id="46217-111">SitePhpErrorLogFlag クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46217-111">Initializes a new instance of the SitePhpErrorLogFlag class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalLogErrors">
      <MemberSignature Language="C#" Value="public string LocalLogErrors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalLogErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.LocalLogErrors" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalLogErrors As String" />
      <MemberSignature Language="F#" Value="member this.LocalLogErrors : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.LocalLogErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localLogErrors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46217-112">取得またはローカル log_errors 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-112">Gets or sets local log_errors setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalLogErrorsMaxLength">
      <MemberSignature Language="C#" Value="public string LocalLogErrorsMaxLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalLogErrorsMaxLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.LocalLogErrorsMaxLength" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalLogErrorsMaxLength As String" />
      <MemberSignature Language="F#" Value="member this.LocalLogErrorsMaxLength : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.LocalLogErrorsMaxLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localLogErrorsMaxLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46217-113">取得またはローカル log_errors_max_len 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-113">Gets or sets local log_errors_max_len setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterLogErrors">
      <MemberSignature Language="C#" Value="public string MasterLogErrors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterLogErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.MasterLogErrors" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterLogErrors As String" />
      <MemberSignature Language="F#" Value="member this.MasterLogErrors : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.MasterLogErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.masterLogErrors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46217-114">取得またはマスター log_errors 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-114">Gets or sets master log_errors setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterLogErrorsMaxLength">
      <MemberSignature Language="C#" Value="public string MasterLogErrorsMaxLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterLogErrorsMaxLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.MasterLogErrorsMaxLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterLogErrorsMaxLength As String" />
      <MemberSignature Language="F#" Value="member this.MasterLogErrorsMaxLength : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SitePhpErrorLogFlag.MasterLogErrorsMaxLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.masterLogErrorsMaxLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46217-115">取得またはマスター log_errors_max_len 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="46217-115">Gets or sets master log_errors_max_len setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>