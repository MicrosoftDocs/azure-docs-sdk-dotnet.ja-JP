<Type Name="ClusterVersionDetails" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails">
  <TypeSignature Language="C#" Value="public class ClusterVersionDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterVersionDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterVersionDetails" />
  <TypeSignature Language="F#" Value="type ClusterVersionDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e44b9-101">ServiceFabric ランタイム バージョンの結果の詳細</span><span class="sxs-lookup"><span data-stu-id="e44b9-101">The detail of the ServiceFabric runtime version result</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterVersionDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e44b9-102">ClusterVersionDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e44b9-102">Initializes a new instance of the ClusterVersionDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterVersionDetails (string codeVersion = null, string supportExpiryUtc = null, string environment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string codeVersion, string supportExpiryUtc, string environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional codeVersion As String = null, Optional supportExpiryUtc As String = null, Optional environment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails : string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails (codeVersion, supportExpiryUtc, environment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="supportExpiryUtc" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersion"><span data-ttu-id="e44b9-103">クラスターの ServiceFabric ランタイムのバージョン</span><span class="sxs-lookup"><span data-stu-id="e44b9-103">The ServiceFabric runtime version of the cluster</span></span></param>
        <param name="supportExpiryUtc"><span data-ttu-id="e44b9-104">バージョンのサポートの有効期限の日付</span><span class="sxs-lookup"><span data-stu-id="e44b9-104">The date of expiry of support of the version</span></span></param>
        <param name="environment"><span data-ttu-id="e44b9-105">オペレーティング システムをクラスター化します。</span><span class="sxs-lookup"><span data-stu-id="e44b9-105">Cluster operating system.</span></span> <span data-ttu-id="e44b9-106">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="e44b9-106">Possible values include: 'Windows', 'Linux'</span></span></param>
        <summary>
            <span data-ttu-id="e44b9-107">ClusterVersionDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e44b9-107">Initializes a new instance of the ClusterVersionDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.CodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="codeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e44b9-108">取得または設定、クラスターの ServiceFabric ランタイムのバージョン</span><span class="sxs-lookup"><span data-stu-id="e44b9-108">Gets or sets the ServiceFabric runtime version of the cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Environment">
      <MemberSignature Language="C#" Value="public string Environment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Environment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.Environment" />
      <MemberSignature Language="VB.NET" Value="Public Property Environment As String" />
      <MemberSignature Language="F#" Value="member this.Environment : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.Environment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e44b9-109">取得またはクラスター オペレーティング システムを設定します。</span><span class="sxs-lookup"><span data-stu-id="e44b9-109">Gets or sets cluster operating system.</span></span> <span data-ttu-id="e44b9-110">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="e44b9-110">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportExpiryUtc">
      <MemberSignature Language="C#" Value="public string SupportExpiryUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SupportExpiryUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.SupportExpiryUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportExpiryUtc As String" />
      <MemberSignature Language="F#" Value="member this.SupportExpiryUtc : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.SupportExpiryUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportExpiryUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e44b9-111">取得または設定のバージョンのサポートの有効期限の日付</span><span class="sxs-lookup"><span data-stu-id="e44b9-111">Gets or sets the date of expiry of support of the version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>