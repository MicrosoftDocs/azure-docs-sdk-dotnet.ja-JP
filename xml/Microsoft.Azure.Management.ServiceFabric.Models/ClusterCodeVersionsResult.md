<Type Name="ClusterCodeVersionsResult" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult">
  <TypeSignature Language="C#" Value="public class ClusterCodeVersionsResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterCodeVersionsResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterCodeVersionsResult" />
  <TypeSignature Language="F#" Value="type ClusterCodeVersionsResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="114b2-101">ServiceFabric ランタイム バージョンの結果</span><span class="sxs-lookup"><span data-stu-id="114b2-101">The result of the ServiceFabric runtime versions</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCodeVersionsResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="114b2-102">ClusterCodeVersionsResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="114b2-102">Initializes a new instance of the ClusterCodeVersionsResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCodeVersionsResult (string id = null, string name = null, string type = null, string codeVersion = null, string supportExpiryUtc = null, string environment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string codeVersion, string supportExpiryUtc, string environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional codeVersion As String = null, Optional supportExpiryUtc As String = null, Optional environment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult (id, name, type, codeVersion, supportExpiryUtc, environment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="supportExpiryUtc" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="114b2-103">結果の id</span><span class="sxs-lookup"><span data-stu-id="114b2-103">The identification of the result</span></span></param>
        <param name="name"><span data-ttu-id="114b2-104">結果の名前</span><span class="sxs-lookup"><span data-stu-id="114b2-104">The name of the result</span></span></param>
        <param name="type"><span data-ttu-id="114b2-105">結果のリソースの種類</span><span class="sxs-lookup"><span data-stu-id="114b2-105">The result resource type</span></span></param>
        <param name="codeVersion"><span data-ttu-id="114b2-106">クラスターの ServiceFabric ランタイムのバージョン</span><span class="sxs-lookup"><span data-stu-id="114b2-106">The ServiceFabric runtime version of the cluster</span></span></param>
        <param name="supportExpiryUtc"><span data-ttu-id="114b2-107">バージョンのサポートの有効期限の日付</span><span class="sxs-lookup"><span data-stu-id="114b2-107">The date of expiry of support of the version</span></span></param>
        <param name="environment"><span data-ttu-id="114b2-108">オペレーティング システムをクラスター化します。</span><span class="sxs-lookup"><span data-stu-id="114b2-108">Cluster operating system.</span></span> <span data-ttu-id="114b2-109">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="114b2-109">Possible values include: 'Windows', 'Linux'</span></span></param>
        <summary>
            <span data-ttu-id="114b2-110">ClusterCodeVersionsResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="114b2-110">Initializes a new instance of the ClusterCodeVersionsResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.CodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.codeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="114b2-111">取得または設定、クラスターの ServiceFabric ランタイムのバージョン</span><span class="sxs-lookup"><span data-stu-id="114b2-111">Gets or sets the ServiceFabric runtime version of the cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Environment">
      <MemberSignature Language="C#" Value="public string Environment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Environment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Environment" />
      <MemberSignature Language="VB.NET" Value="Public Property Environment As String" />
      <MemberSignature Language="F#" Value="member this.Environment : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Environment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="114b2-112">取得またはクラスター オペレーティング システムを設定します。</span><span class="sxs-lookup"><span data-stu-id="114b2-112">Gets or sets cluster operating system.</span></span> <span data-ttu-id="114b2-113">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="114b2-113">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
            <span data-ttu-id="114b2-114">取得または設定の結果の識別</span><span class="sxs-lookup"><span data-stu-id="114b2-114">Gets or sets the identification of the result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="114b2-115">取得または設定の結果の名前</span><span class="sxs-lookup"><span data-stu-id="114b2-115">Gets or sets the name of the result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportExpiryUtc">
      <MemberSignature Language="C#" Value="public string SupportExpiryUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SupportExpiryUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.SupportExpiryUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportExpiryUtc As String" />
      <MemberSignature Language="F#" Value="member this.SupportExpiryUtc : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.SupportExpiryUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportExpiryUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="114b2-116">取得または設定のバージョンのサポートの有効期限の日付</span><span class="sxs-lookup"><span data-stu-id="114b2-116">Gets or sets the date of expiry of support of the version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="114b2-117">取得または設定の結果のリソースの種類</span><span class="sxs-lookup"><span data-stu-id="114b2-117">Gets or sets the result resource type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>